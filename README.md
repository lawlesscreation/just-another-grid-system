# Just Another Grid System (JAGS)

> A CSS grid system created for developing consistent, responsive and liquid grids.

 - [View on GitHub](https://github.com/lawlesscreation/just-another-grid-system)
 - [Download ZIP](https://github.com/lawlesscreation/just-another-grid-system/archive/master.zip)


## Usage

To get started you can either:

 - Clone the repo: `git clone https://github.com/lawlesscreation/just-another-grid-system.git`
 - Or install with Bower: `bower install just-another-grid-system`

Then it's just a case of adding the CSS file to your HTML:

```html
<link rel="stylesheet" media="all" href="path/to/jags.css" />
```

Or import the SCSS file into your main SCSS project:

```scss
@import "path/to/jags.scss";
```

Finally, take a look at the [different layouts](http://lawlesscreation.github.io/just-another-grid-system/gh-pages/layouts.html) to find the grid you require. You can nest the code to create even more [complex grids](http://lawlesscreation.github.io/just-another-grid-system/gh-pages/extreme-testing.html)!

If you need Internet Explorer support for IE7-IE8 you will need a JavaScript polyfill for the CSS media queries, such as [Respond](https://github.com/scottjehl/Respond), which should be added to the `<head>`:

```html
<script src="js/respond/respond.min.js"></script>
```


## Development

### SCSS

If you need to change some of the defaults like the media query breakpoints, margins or borders you can do using the `_vars.scss` and recompile the `jags.css` file:

```bash
$ sass jags.scss:jags.css --style expanded
```

or compressed:

```bash
$ sass jags.scss:jags.min.css --style compressed --sourcemap=none
```

## Some notes
There are a few things you might like to know...

### Mobile-first

The media queries have been structured with a "mobile-first" approach from 0px up, but feel free to customise them if you wish!

### Equal height columns

By default JAGS doesn't come with the equal height columns script that I'm using here, but feel free to use the one in the demo.

### Works in IE6?!

Yes and no. The grids work fine with the exception of the border variations because IE6's support for adjoining classes is a little flakey.


## Major and minor release history

- 3.0.0 Added new grid variations (33/66, 25/75);
- 2.1.0 Added project to bower;
- 2.0.0 Adopted loose BEM syntax for better CSS performance;
- 1.1.0 Changed to semantic versioning.

Copyright &copy; 2013 [@lawlesscreation](http://twitter.com/lawlesscreation)

Licensed under [MIT](http://opensource.org/licenses/mit-license.php)


## TODO

 - Nothing.