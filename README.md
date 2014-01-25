# Just Another Grid System (JAGS)
###### A responsive, liquid grid system designed for fast and effective CSS layouts.

 - [View on GitHub](https://github.com/lawlesscreation/just-another-grid-system)
 - [Download ZIP](https://github.com/lawlesscreation/just-another-grid-system/archive/master.zip)


## Usage

Simply add the CSS file:

```html
<link rel="stylesheet" media="all" href="css/jags.min.css" />
```

Then look at the [different layouts](http://lawlesscreation.github.io/just-another-grid-system/gh-pages/layouts.html) to find the grid you require. You can nest the code to create even more [complex grids](http://lawlesscreation.github.io/just-another-grid-system/gh-pages/extreme-testing.html)!

If you need Internet Explorer support for IE7-IE8 you will need a JS polyfill for CSS3 Media Queries, such as [Respond](https://github.com/scottjehl/Respond) which should be added to the <code>&lt;head&gt;</code>:

```html
<script src="js/respond/respond.min.js"></script>
```


## SCSS

If you need to change some of the defaults like the media query breakpoints, margins or borders you can do using the <code>_vars.scss</code> and recompile using:

```bash
$ sass jags.scss:jags.min.css --style compressed
```

or expanded:

```bash
$ sass jags.scss:jags.css --style expanded
```


## Some notes
There are a few things you might like to know...

### Mobile-first

The media queries have been structured in a "mobile-first" approach from 0px up, but feel free to customise they how you wish!

### Equal height columns

By default JAGS doesn't come with the equal height columns script that I'm using here, but feel free to use the one in the demo.

### What about IE6?

IE6 was supported but has been dropped since version 0.4 of JAGS. That said, it can be done and requires a JavaScript <em>polyfill</em> called [Selectivizr](http://selectivizr.com/) for CSS attribute selector support.


## Release history

 - v1.1.0 Changed to semantic versioning (2014-01-25)
 - v1.1 Includes 1/6 grid and improvements (2013-12-12)
 - v1.0 Stable version for 1.0 release (2013-08-09)

Copyright © 2013 [@lawlesscreation](http://twitter.com/lawlesscreation)

Licensed under [MIT](http://opensource.org/licenses/mit-license.php)


## TODO

 - Nothing.
