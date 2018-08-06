# CSS3 Grid Pattern (postcss)
## Version 1.0

Created by Tracey Holinka (https://traceyholinka.com/) April 2017.
Use PostCSS custom properties to create the most common design grids.

CSS3 Grid is supported by:

* Chrome 57+
* Firefox 53+
* IE 10+
* IOS Safari 10.3+
* Android Chrome 57+

IE10 & IE11 does not have a gap property so the gaps are represented by a column. For example a 4 column mobile grid having 3 column gaps is represent by a total of 7 columns.

1 column 1 gap 1 column 1 gap 1 column 1 gap 1 column

To represent 4 columns with whitespace gaps:

* column 1: grid-column: 1
* column 2: grid-column: 3
* column 3: grid-column: 5
* column 4: grid-column: 7

This grid is fully responsive by using <code>fr</code> for columns while gaps are static. Mobile view are a 4 column grid. Tablet and above is a 12 column grid.
