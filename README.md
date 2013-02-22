# HTML5-Skeleton

## About

This HTML5-Skeleton consists of the very bare essentials of most of the projects I work on. Because sharing really is caring I figured that putting this on GitHub might be a noble thing to do.

## Third party Libraries

### [Normalize.css](http://necolas.github.com/normalize.css/)

> Normalize.css makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing.

### [jQuery](http://jquery.com/)

> jQuery is a fast and concise JavaScript Library that simplifies HTML document traversing, event handling, animating, and Ajax interactions for rapid web development. jQuery is designed to change the way that you write JavaScript.

### [html5shiv](https://code.google.com/p/html5shiv/)
> html5shiv adds new HTML5 elements (which is simple code), but also supports printing HTML5 elements and includes the default styles for HTML5 elements, like block on article and section.

### [Selectivizr](http://selectivizr.com/)
> selectivizr is a JavaScript utility that emulates CSS3 pseudo-classes and attribute selectors in Internet Explorer 6-8.

## Cross-browser

Since each project entails some Internet Explorer issues, I made sure that some classes will be added to the `<html>`-tag when the page is being viewed in a certain version of Internet Explorer.

These classes are:
* `.lt-ie9`
* `.lt-ie8`
* `.lt-ie7`

If JavaScript isn't enabled in the browser, the class `.no-js` will also be added to the `<html>`-tag