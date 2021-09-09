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


Principles for writing good css

-Responsive Design
 -Maintainable and scalable code
 -Media Queries
 -Responsive Images
 -Correct units
 -Desktop first vs mobile-first

-Maintainable and Scalable Code
 -Clean
 -Easy to understand
 -Growth
 -Reusable
 -How to organize files
 -How to name classes
 -How to structure html

-Web Performance
 -Less HTTP request
 -Less code
 -Compressed code
 -Use a css preprocessor
 -Less images
 -Compressed images


use rem units as they are relative to a specific global font size.
Even margin, padding and everything else in rem will be calculated based on global font size

eg set root font size is 10px ==> Always set 10px. This is a rule.

so 1rem = 10px.  2rem = 20px , 2.4rem = 24px  and so on.

html{
    font-size:10px;
}

10px makes calculation easy. that is why we keep it 10px.


em are a bit hard to work as they depend on root font size and also on parent font size.

