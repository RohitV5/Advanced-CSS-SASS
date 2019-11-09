# Advanced-CSS-SASS
Using CSS and SASS


Responsive Web Design



Component Driven Design


BEM : Block Element MOdifier 

The 7-1 Pattern : 7 different folder for partial Sass Files, and 1 main Sass File to Import all other files into a compiled CSS Stylesheet
base/ components/ layouts/ pages/ themes/ abstracts/ vendors/


SASS gives us variables , nesting, operators, partails and imports, mixins and functions,extends, control directives


DRY principle : Dont repeat yourself use @mixin sass



SCRIPT to Compile SASS --> node-sass sass/main.scss css/style.css -w
Take main.scss from sass folder and make a style.css in css folder. Voila! Simple. 
-w is watch flag which watches any scss changes