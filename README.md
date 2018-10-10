# Sass Boilerplate
My Sass experience

- - - -

### File Structure
The boilerplate contains the entire directory structure needed for a frontend project and can be easily integrated into any project type.

- - - -

### Settings - [/settings](https://github.com/tsankashvili/sass-boilerplate/tree/master/settings)
This layer contains all of the variables needed to turn settings on and off as well as setting global values for commonly used properties.

- - - -

### Validators - [/validators](https://github.com/tsankashvili/sass-boilerplate/tree/master/validators)
Validators files are private helpers for mixins and functions.

- - - -

### Functions - [/functions](https://github.com/tsankashvili/sass-boilerplate/tree/master/functions)
Many useful functions for manipulating colors and other values.The functions layer contains a number of useful mathematical functions.

- - - -

### Mixins - [/mixins](https://github.com/tsankashvili/sass-boilerplate/tree/master/mixins)
Many useful mixins for manipulating breakpoints and other values,
mixins can be added by creating new files. Since mixins don't output any code until they're used there is no harm in them being there and not being utilised.

- - - -

### Generic - [/generic](https://github.com/tsankashvili/sass-boilerplate/tree/master/generic)
reset and/or normalize styles etc. This is the first layer which generates actual CSS.

- - - -

### Base - [/base](https://github.com/tsankashvili/sass-boilerplate/tree/master/base)
The base layer is for the styling of common elements without the use of classnames, these are very generic and far reaching styles affecting all instances of any given element.

- - - -

### Objects - [/objects](https://github.com/tsankashvili/sass-boilerplate/tree/master/objects)
The objects layer contains a number of classed elements. Along with the components layer most of your time will be spent here. This is where you will add new files for the objects in your project. The files included are as follows;

- - - -

### Animations - [/animations](https://github.com/tsankashvili/sass-boilerplate/tree/master/animations)
Any CSS animations used in the project.

- - - -

### Layouts - [/layouts](https://github.com/tsankashvili/sass-boilerplate/tree/master/layouts)
The layout/ directory (sometimes called partials/) usually contains a number of files, each of them setting some styles for the main sections of the layout (header, footer, and so on).

- - - -

### Components - [/components](https://github.com/tsankashvili/sass-boilerplate/tree/master/components)
For smaller components. It can contain all kinds of specific modules like a slider, a loader, a widget, or anything along those lines. There are usually a lot of files in components/ since your site is should be mostly composed of tiny modules.

- - - -

### Pages - [/pages](https://github.com/tsankashvili/sass-boilerplate/tree/master/pages)
If you have page-specific styles, I think it’s cool to put them in a pages/ folder and in a file named after the page.

- - - -

### Overrides - [/overrides](https://github.com/tsankashvili/sass-boilerplate/tree/master/overrides)
The overrides layer contains the helper classes broken down into multiple files for different property types and the shame file used for quick and dirty fixes.

- - - -

### Vendors - [/validators](https://github.com/tsankashvili/sass-boilerplate/tree/master/vendors)
And last you will probably have a vendors/ folder containing all the CSS files from external libraries and frameworks

- - - -

### app.scss - [app.scss](https://github.com/tsankashvili/sass-boilerplate/tree/master/app.scss)
The app.scss file is where the entire project is stitched together. Consisting only of @import rules it is responsible for the order in which the code is output into the single main stylesheet when compiled.


## Sass libraries, files and folders structures
Thank you very much. I learned a lot from them and I agree in many ways:

- [Bourbon](https://www.bourbon.io/) - pure Sass mixins and functions,
- [Compass](http://compass-style.org/) - CSS Authoring Framework,
- [Hugo Giraudel](https://sass-guidelin.es/) - Sass Guidelines,
- [Hugo Giraudel](https://hugogiraudel.com/) - Hugo Giraudel's blog,
- [BetterBoilerplate](https://github.com/BetterBrandAgency/betterboilerplate) - A frontend framework,
- [css-tricks](https://css-tricks.com/) - Tips, Tricks, and Techniques on using css,
- [breakpoint-sass](http://breakpoint-sass.com/) - Breakpoint makes writing media queries in Sass super simple.
