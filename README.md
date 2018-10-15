# Sass Boilerplate
My Sass experience

- - - -

### Directory and file structure
The boilerplate contains the entire directory structure needed for a frontend project and can be easily integrated into any project type.


    ├── settings
    │   ├── base-options.scss
    │   ├── fonts-text.scss
    │   ├── colors.scss
    │   ├── modules-widgets.scss
    │   ├── global-properties.scss
    │   ├── breakpoints.scss
    │   ├── animations.scss
    │   ├── easings.scss
    │   ├── transitions.scss
    │   └── z-index.scss
    ├── validators
    │   ├── contains.scss
    │   ├── is-length.scss
    │   ├── is-color.scss
    │   └── is-size.scss
    ├── functions
    │   ├── sh-setup.scss
    │   ├── math.scss
    │   ├── map-functions.scss
    │   ├── list-functions.scss
    │   ├── unitconversion.scss
    │   ├── to-number.scss
    │   ├── string-replace.scss
    │   ├── strip-unit.scss
    │   ├── breakpoints-map.scss
    │   ├── animations.scss
    │   ├── easings.scss
    │   ├── color.scss
    │   ├── tint.scss
    │   ├── shade.scss
    │   └── z-index.scss
    ├── mixins
    │   ├── border-radius.scss
    │   ├── breakpoints.scss
    │   ├── centering.scss
    │   ├── circle.scss
    │   ├── clearfix.scss
    │   ├── fonts.scss
    │   ├── hide.scss
    │   ├── strip-unit.scss
    │   ├── line-clamp.scss
    │   ├── nth-child.scss
    │   ├── placeholder.scss
    │   ├── position.scss
    │   ├── pseudo.scss
    │   ├── resize.scss
    │   ├── scrollbars.scss
    │   ├── selection.scss
    │   ├── size.scss
    │   ├── text-crop.scss
    │   ├── triangle.scss
    │   ├── visually-hidden.scss
    │   └── z-index.scss
    ├── generic
    │   ├── reset.scss
    │   └── sanitize.scss
    ├── base
    │   ├── config.scss
    │   ├── global.scss
    │   └── typography.scss
    ├── objects
    │   ├── colors-classes.scss
    │   ├── images.scss
    │   └── svg.scss
    ├── animations
    │   └── bouncing.scss
    ├── layouts
    │   ├── grid.scss
    │   └── main.scss
    ├── components
    │   ├── header.scss
    │   └── footer.scss
    ├── pages
    │   ├── about.scss
    │   ├── contact.scss
    │   └── home.scss
    ├── overrides
    │   ├── helper-float.scss
    │   ├── helper-margin.scss
    │   ├── helper-padding.scss
    │   ├── helper-position.scss
    │   ├── helper-text.scss
    │   ├── helper-visibility.scss
    │   └── shame.scss
    ├── vendors
    │   └── breakpoint-sass
    │       └── _breakpoint.scss
    └── app.scss 

- - - -

### Settings - [/settings](/settings)
This layer contains all of the variables needed to turn settings on and off as well as setting global values for commonly used properties.

<details>
  <summary>View files</summary>

  * [`base-options.scss`](/settings/base-options.scss)
  * [`fonts-text.scss`](/settings/fonts-text.scss)
  * [`colors.scss`](/settings/colors.scss)
  * [`modules-widgets.scss`](/settings/modules-widgets.scss)
  * [`global-properties.scss`](/settings/global-properties.scss)
  * [`breakpoints.scss`](/settings/breakpoints.scss)
  * [`animations.scss`](/settings/animations.scss)
  * [`easings.scss`](/settings/easings.scss)
  * [`transitions.scss`](/settings/transitions.scss)
  * [`z-index.scss`](/settings/z-index.scss)

</details>

- - - -

### Validators - [/validators](/validators)
Validators files are private helpers for mixins and functions.

<details>
  <summary>View files</summary>

  * [`contains.scss`](/validators/contains.scss)
  * [`is-length.scss`](/validators/is-length.scss)
  * [`is-color.scss`](/validators/is-color.scss)
  * [`is-size.scss`](/validators/is-size.scss)

</details>

- - - -

### Functions - [/functions](/functions)
Many useful functions for manipulating colors and other values.The functions layer contains a number of useful mathematical functions.

<details>
  <summary>View files</summary>

  * [`sh-setup.scss`](/functions/sh-setup.scss)
  * [`math.scss`](/functions/math.scss)
  * [`map-functions.scss`](/functions/map-functions.scss)
  * [`list-functions.scss`](/functions/list-functions.scss)
  * [`unitconversion.scss`](/functions/unitconversion.scss)
  * [`to-number.scss`](/functions/to-number.scss)
  * [`string-replace.scss`](/functions/string-replace.scss)
  * [`strip-unit.scss`](/functions/strip-unit.scss)
  * [`breakpoints-map.scss`](/functions/breakpoints-map.scss)
  * [`animations.scss`](/functions/animations.scss)
  * [`easings.scss`](/functions/easings.scss)
  * [`color.scss`](/functions/color.scss)
  * [`tint.scss`](/functions/tint.scss)
  * [`shade.scss`](/functions/shade.scss)
  * [`z-index.scss`](/functions/z-index.scss)

</details>

- - - -

### Mixins - [/mixins](/mixins)
Many useful mixins for manipulating breakpoints and other values,
mixins can be added by creating new files. Since mixins don't output any code until they're used there is no harm in them being there and not being utilised.

<details>
  <summary>View files</summary>

  * [`border-radius.scss`](/mixins/border-radius.scss)
  * [`breakpoints.scss`](/mixins/breakpoints.scss)
  * [`centering.scss`](/mixins/centering.scss)
  * [`circle.scss`](/mixins/circle.scss)
  * [`clearfix.scss`](/mixins/clearfix.scss)
  * [`fonts.scss`](/mixins/fonts.scss)
  * [`hide.scss`](/mixins/hide.scss)
  * [`letter-spacing.scss`](/mixins/letter-spacing.scss)
  * [`line-clamp.scss`](/mixins/line-clamp.scss)
  * [`nth-child.scss`](/mixins/nth-child.scss)
  * [`placeholder.scss`](/mixins/placeholder.scss)
  * [`position.scss`](/mixins/position.scss)
  * [`pseudo.scss`](/mixins/pseudo.scss)
  * [`resize.scss`](/mixins/resize.scss)
  * [`scrollbars.scss`](/mixins/scrollbars.scss)
  * [`selection.scss`](/mixins/selection.scss)
  * [`size.scss`](/mixins/size.scss)
  * [`text-crop.scss`](/mixins/text-crop.scss)
  * [`triangle.scss`](/mixins/triangle.scss)
  * [`visually-hidden.scss`](/mixins/visually-hidden.scss)
  * [`z-index.scss`](/mixins/z-index.scss)

</details>

- - - -

### Generic - [/generic](/generic)
reset and/or normalize styles etc. This is the first layer which generates actual CSS.

<details>
  <summary>View files</summary>

  * [`reset.scss`](/generic/reset.scss)
  * [`sanitize.scss`](/generic/sanitize.scss)

</details>

- - - -

### Base - [/base](/base)
The base layer is for the styling of common elements without the use of classnames, these are very generic and far reaching styles affecting all instances of any given element.

<details>
  <summary>View files</summary>

  * [`config.scss`](/base/config.scss)
  * [`global.scss`](/base/global.scss)
  * [`typography.scss`](/base/typography.scss)

</details>

- - - -

### Objects - [/objects](/objects)
The objects layer contains a number of classed elements. Along with the components layer most of your time will be spent here. This is where you will add new files for the objects in your project. The files included are as follows;

<details>
  <summary>View files</summary>

  * [`colors-classes.scss`](/objects/colors-classes.scss)
  * [`images.scss`](/objects/images.scss)
  * [`svg.scss`](/objects/svg.scss)

</details>

- - - -

### Animations - [/animations](/animations)
Any CSS animations used in the project.

<details>
  <summary>View files</summary>

  * [`bouncing.scss`](/animations/bouncing.scss)

</details>

- - - -

### Layouts - [/layouts](/layouts)
The layout/ directory (sometimes called partials/) usually contains a number of files, each of them setting some styles for the main sections of the layout (header, footer, and so on).

<details>
  <summary>View files</summary>


  * [`bouncing.scss`](/layouts/grid.scss)
  * [`main.scss`](/layouts/main.scss)

</details>

- - - -

### Components - [/components](/components)
For smaller components. It can contain all kinds of specific modules like a slider, a loader, a widget, or anything along those lines. There are usually a lot of files in components/ since your site is should be mostly composed of tiny modules.

<details>
  <summary>View files</summary>

  * [`header.scss`](/components/header.scss)
  * [`footer.scss`](/components/footer.scss)

</details>

- - - -

### Pages - [/pages](/pages)
If you have page-specific styles, I think it’s cool to put them in a pages/ folder and in a file named after the page.

<details>
  <summary>View files</summary>

  * [`about.scss`](/pages/about.scss)
  * [`contact.scss`](/pages/contact.scss)
  * [`home.scss`](/pages/home.scss)

</details>

- - - -

### Overrides - [/overrides](/overrides)
The overrides layer contains the helper classes broken down into multiple files for different property types and the shame file used for quick and dirty fixes.

<details>
  <summary>View files</summary>

  * [`helper-float.scss`](/overrides/helper-float.scss)
  * [`helper-margin.scss`](/overrides/helper-margin.scss)
  * [`helper-padding.scss`](/overrides/helper-padding.scss)
  * [`helper-position.scss`](/overrides/helper-position.scss)
  * [`helper-text.scss`](/overrides/helper-text.scss)
  * [`helper-visibility.scss`](/overrides/helper-visibility.scss)
  * [`shame.scss`](/overrides/shame.scss)

</details>

- - - -

### Vendors - [/Vendors](/vendors)
And last you will probably have a vendors/ folder containing all the CSS files from external libraries and frameworks

<details>
  <summary>View files</summary>

  * [`_breakpoint.scss`](/vendors/breakpoint-sass/_breakpoint.scss)

</details>

- - - -

### app.scss - [app.scss](/app.scss)
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

## Other awesome resources
- [jump start sass](https://www.goodreads.com/book/show/26598681-jump-start-sass) - Book by Hugo Giraudel and Miriam Suzanne
