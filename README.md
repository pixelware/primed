# Primed UI

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Primed is a front-end design toolkit built with Sass for developing simple responsive landing pages.

Primed offers a variety of complementary font family combinations which can be set for the compiled CSS code output by changing a single Sass variable. Another Sass variable change will compile the CSS to a dark UI version of Primed.

Primed also provides browser-consistent styling for default HTML elements such as buttons, forms, tables, lists, and typography.

Primed form validation is built in using a slightly modified version of the third party javascript library [PristineJS](https://pristine.js.org/).

Primed is in release v1.0 and works in all modern browsers. I've even gone to great lengths to make Primed work with Internet Explorer 11. Why? 
Because many corporates still use this outdated browser across their IT systems.

Primed is pretty lightweight when compared to some rival CSS UI Frameworks and weighs in at 28kb when minified. 

## Documentation

### [View documentation](https://pixelware.github.io/primed)

## Installation

- [Download the zipped archive](https://github.com/pixelware/primed/archive/master.zip). You'll find the Primed CSS stylesheet in the `dist/css` folder. Choose between the uncompressed stylesheet `primed.css` or the minified version `primed.min.css`
- Save the stylesheet to your project and link to it in the HEAD of your HTML files. A boilerplate `boilerplate.html` file is included in the `dist` folder.

### Using Sass (recommended)

While a 'ready-to-go' compiled CSS file is made available in the `dist` folder, to get the best out of this framework you can create unique designs by changing the variables in the Saas config file `_config.scss`.

By simply making one variable change you can output a dark CSS version of the Primed Framework. Likewise, you can switch between several complementary font family pairings by changing just one variable in the config file.

All of Primed's colors, typography, sizes, breakpoints, buttons, borders, and more are defined in the `_config.scss` file.

After Sass compilation you can view `dist/index.html` to see how your changes affect the most common HTML elements in a web page.


### Gulp usage

Sass compilation to CSS is achieved using [GulpJS](https://gulpjs.com/). Make sure you download and install Gulp on your development machine and install all the required Node Modules using NPM as listed in the `gulpfile.js`.

- To build the CSS: run `gulp`
- To watch for modifications, recompile CSS and refresh the browser: run `gulp watch`

```bash
# Build a minified production build
gulp

# Watch for file changes, re-build, and refresh the browser preview
gulp watch
```

## Acknowledgements

- Chris Ferdinandi for building [Gulp Boilerplate](https://github.com/cferdinandi/gulp-boilerplate), a boilerplate for building web projects with Gulp.js.
- [Tania Rascia](https://www.taniarascia.com) whose documentation for her Primitive UI greatly inspired the documentation for Primed. Tania has 
some excellent web development articles on her website which I recommend for aspiring devs.

## Contributing

Please feel free to fork, comment, critique, or submit a pull request.

## Author

- [Andy Thompson](https://pixelpersuasion.com)

## License

This project is open source and available under the [MIT License](LICENSE.md).