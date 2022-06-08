# SASS-mini-project

A landing page header to display things like variables, nesting, mixins, etc using SASS

## Notes about SASS

SASS: Syntactically Awesome StyleSheets

- a CSS preProcessor / Extension
- let's you use features that don't exist in CSS
- .scss files are compiled to regular CSS
- easy to compile with Live SASS compiler extension in VS Code

### Common uses

- $variablename is like using root in CSS
- nest tags within to reduce redundancy
- functions and mixins allow for the creation of blocks of CSS that can be run anywhere
- inheritance can be applied efficiently with @extend
- operators are possible for calculations. less used
- conditionals uisng if, else, include can be useful (like js)

- It's a good idea to create a \_config.scss file for variables, mix-ins, functions, etc
- the underscore in \_config.scss identifies the file as a partial (to bring into another file, not to be compiled on it's own like style.scss)
- then @import 'config'; into the style.scss, no underscore needed
- repeat for utilities, buttons, etc and import to scss stylesheet

- use functions and conditionals to match background color with appropriate legible font color

- for mixins create the @mixin function and remember to use @include to apply wherever needed

- creating loops. look at example in utilities for margin space based on paragraph class.

- for responsiveness, create a \_mobile.scss file for media queries. @import at BOTTOM of style.scss file
