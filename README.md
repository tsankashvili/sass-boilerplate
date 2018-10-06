# SASS Boilerplate
My sass experience

- - - -

### File Structure
The boilerplate contains the entire directory structure needed for a frontend project and can be easily integrated into any project type.

- - - -

#### settings
This layer contains all of the variables needed to turn settings on and off as well as setting global values for commonly used properties.

- - - -

#### validators
Validators files are private helpers for mixins and functions.

- - - -

#### functions
Many useful functions for manipulating colors and other values.The functions layer contains a number of useful mathematical functions.

- - - -

#### mixins
Many useful mixins for manipulating breakpoints and other values,
mixins can be added by creating new files. Since mixins don't output any code until they're used there is no harm in them being there and not being utilised.

- - - -

#### generic
reset and/or normalize styles, box-sizing definition, etc. This is the first layer which generates actual CSS.

- - - -

#### base
The base layer is for the styling of common elements without the use of classnames, these are very generic and far reaching styles affecting all instances of any given element.


- - - -

#### objects
The objects layer contains a number of classed elements. Along with the components layer most of your time will be spent here. This is where you will add new files for the objects in your project. The files included are as follows;


- - - -

#### animations
Any CSS animations used in the project.

- - - -

#### layouts
The layout/ directory (sometimes called partials/) usually contains a number of files, each of them setting some styles for the main sections of the layout (header, footer, and so on).

- - - -

#### components
For smaller components. It can contain all kinds of specific modules like a slider, a loader, a widget, or anything along those lines. There are usually a lot of files in components/ since your site is should be mostly composed of tiny modules.

- - - -

#### pages
If you have page-specific styles, I think it’s cool to put them in a pages/ folder and in a file named after the page.

- - - -

#### overrides
The overrides layer contains the helper classes broken down into multiple files for different property types and the shame file used for quick and dirty fixes.

- - - -

#### vendors
And last you will probably have a vendors/ folder containing all the CSS files from external libraries and frameworks

- - - -

#### app.scss
The app.scss file is where the entire project is stitched together. Consisting only of @import rules it is responsible for the order in which the code is output into the single main stylesheet when compiled.

- - - -
