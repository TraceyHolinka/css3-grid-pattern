# CSS3 Grid Pattern

## Version 2.0

Created by Tracey Holinka (https://traceyholinka.com/)

Native CSS patterns to create the most common design grids.

CSS3 Grid is supported by:

* Chrome 57+
* Firefox 53+
* IE 10+
* IOS Safari 10.3+
* Android Chrome 57+

PostCSS Autoprefixer now handles simple grid CSS for IE 10/11 well so I've removed the IE 10/11 specific prefix code, but I still write with IE 10/11 in mind. Currently grid support is turned off by default so you'll need to enable it to support IE 10/11. If you want to get fancy, it is still better to write the code for IE 10/11 yourself.

IE10/11 does not have a gap property so the gaps are represented by a column. For example a 4 column mobile grid
having 3 column gaps is represent by a total of 7 columns. Even if you use PostCSS Autoprefixer for IE 10/11 support, I recommend maintaining this pattern.

1 column 1 gap 1 column 1 gap 1 column 1 gap 1 column

To represent 4 columns with whitespace gaps:

* column 1: grid-column: 1
* column 2: grid-column: 3
* column 3: grid-column: 5
* column 4: grid-column: 7

This grid is fully responsive by using <code>fr</code> for columns while gaps are static. Mobile view are a 4 column grid. Tablet and above is a 12 column grid.

Note: This is a pattern. It is not ment for you to use these classes in your work but to provide an example of how to
add native CSS grid directly to your CSS.
