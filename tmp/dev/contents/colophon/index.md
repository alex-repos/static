---
title: Colophon
subtitle: How this site was created, what tools it uses, and how to access the source code
author: David Tucker
date: 2013-01-02
template: colophon.html
keywords: copyright,usage,policy,license
changefreq: monthly
priority: 0.5
---

This site was built on [Wintersmith](http://jnordberg.github.com/wintersmith/), a NodeJS static site generator created by [Johan Nordberg](https://github.com/jnordberg).  It uses [Nunjucks](http://nunjucks.jlongster.com/) for templating with the [wintersmith-nunjucks](https://github.com/jbuck/wintersmith-nunjucks) plugin created by [Jon Buckley](https://github.com/jbuck).  The site uses sematically-accurate HTML5 and CSS3 styling.

The site's responsive grid is based on [Foundation 4](http://foundation.zurb.com/) by [Zurb](http://zurb.com/) (which in turn uses [SASS](http://sass-lang.com/)).  There are many parts of foundation that are not used, but I did take advantage of the grid and some provided mixins. 

## Typography

I am actually using a mixed approach for typography.  On Mac and iOS, I am using included fonts (Helvetica Neue, Helvetica Neue Condensed) to minimize the number of resources loaded at runtime.  On all other platforms, I am using the [Google Web Fonts](http://www.google.com/webfonts) [Roboto](http://www.google.com/webfonts/specimen/Roboto), [Roboto Condensed](http://www.google.com/webfonts/specimen/Roboto+Condensed) and [Cardo](http://www.google.com/webfonts/specimen/Cardo).

## Tools

All raster graphics were created in Adobe Photoshop and all vector graphics including the logo were created in Adobe Illustrator.  All code was written in a licensed version of [Sublime Text 2](http://www.sublimetext.com/2).  I tracked tasks in [Trello](http://www.trello.com) during development (and will track future improvements there too).

## Testing

For testing, I utilized <a href="http://www.browserstack.com/" target="_blank">BrowserStack</a> to ensure my site works properly across my targeted browsers (IE9+, Firefox 3+, Chrome x+, Safari x+, iOS 4.3+, and Android 2.2+).  I used <a href="http://modernizr.com/" target="_blank">Modernizr</a> to detect supported features and adjust the display of a warning banner is not all required features were supported.

## Hosting & Deployment

The site is currently hosted on Amazon S3.  I use [Grunt](http://gruntjs.com/) to handle all of the develop, build and deployment processes.  You can check out my [Gruntfile.js](https://github.com/davidtucker/davidtucker-blog/blob/develop/Gruntfile.js) to see how I handle these items.

## Source Code

I have provided the <a href="https://github.com/davidtucker/davidtucker-blog" target="_blank">source code for this site on Github</a> as both an example of my work as well as a tool for other developers looking to create a similar site using Wintersmith.  It is released under an MIT license.