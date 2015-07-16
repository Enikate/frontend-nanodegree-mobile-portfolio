## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository, inspect the code,

### Getting started

####Part 1: Optimize PageSpeed Insights score for index.html
All images was optimised with reduced size and number of colors used. (GIMP + ImageAlpha)

In index.html:
Google font and screen style was embeded into main html file.
Google analitycs and perfmatters chenge to async
Mostly used png for files with reduced number of colors
print.css made so its used just for printing (media=print)

To browse simply use: http://enikate.github.io/frontend-nanodegree-mobile-portfolio/

####Part 2: Optimize Frames per Second in pizza.html

For rendering:

function run on DOMContentLoaded was modified.
Number of pizzas is calculated instead of using always 200.

For scroll:

function updatePositions() was modified.
querySelectorAll was replaced by getElementsByClassName and math calculations was moved outside loop and stored in array so inside we just accessing those.

For size change:

function changePizzaSizes(size) was modified.
newwidth calculation was moved outside the loop and based on 1st element.


