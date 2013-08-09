# Just Another Grid System (JAGS)
###### A responsive, liquid grid system designed for fast and effective CSS layouts.

 - [View on GitHub](https://github.com/lawlesscreation/just-another-grid-system)
 - [Download ZIP](https://github.com/lawlesscreation/just-another-grid-system/archive/master.zip)


## Usage

Simply add the CSS file:

```html
<link rel="stylesheet" media="all" href="css/grids.min.css" />
```

Then look at the [different layouts](https://github.com/lawlesscreation/just-another-grid-system/gh-pages/layouts.html) to find the grid you require. You can nest the code to create even more [complex grids](https://github.com/lawlesscreation/just-another-grid-system/gh-pages/extreme-testing.html)!

If you need Internet Explorer support for IE7-IE8 you will need a JS polyfill for CSS3 Media Queries, such as [Respond](https://github.com/scottjehl/Respond) which should be added to the <code><head></code>:

```html
<script src="js/respond/respond.min.js"></script>
```


## SCSS

If you need to change some of the defaults like the media query breakpoints, margins or borders you can do using the <code>_vars.scss</code> and recompile using:

```bash
$ sass scss/grids.scss css/grids.min.css --style compressed
```

or expanded:

```bash
$ sass scss/grids.scss css/grids.css --style expanded
```


## Some notes
There are a few things you might like to know...

### Mobile-first

The media queries have been structured in a "mobile-first" approach from 0px up, but feel free to customise they how you wish!

### Equal height columns

By default JAGS doesn't come with the equal height columns script I'm using on this page but feel free to use the one in the code.

### What about IE6?

IE6 was supported but has been dropped since version 0.4 of JAGS. That said, it can be done and requires a JavaScript <em>polyfill</em> called [Selectivizr](http://selectivizr.com/) for CSS attribute selector support.


## Release history
 - v1.0 RELEASE. This includes adding to [GitHub pages](http://lawlesscreation.github.io/just-another-grid-system/) (2013-08-09).
 - v0.6 Updated to only include box margin-bottom when in columns, not linear, remove the -fl- or -fr- class when used in combination with the -oh as it is not required.
 - v0.5 Added SCSS and variables to the grid system can be easily configured.
 - v0.4 **Dropped support for IE6** (it can still be done with [Selectivizr](http://selectivizr.com/), but has been removed by default).
 - v0.3 Fixed a few typo inconsistencies. Compressed code a little more.
 - v0.2 Fixed missing CSS for 66/33 and 75/25 split.
 - v0.1 released under the MIT license (2012-03-13).

Copyright © 2013 [@lawlesscreation](http://twitter.com/lawlesscreation)

Licenced under [MIT](http://opensource.org/licenses/mit-license.php)
