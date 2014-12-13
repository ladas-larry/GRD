GRD
=============


Responsive webdesign is great, but it’s not a silver bullet.

So this grid was made in belief, that mobile web should have it's own dedicated layout and shouldn't be mixed with bloated desktop markup and resources.


Moreover what happens after user shrink your responsive site on 11' laptop?
Tablet version. Shouldn't be user free to resize browser window and still get the same desktop layout?

##How to use it

``<link rel="stylesheet" href="https://rawgit.com/Dharmoslap/GRD/master/grid.css">``

You can find a sample [here](http://dharmoslap.github.io/GRD/). Go and inspect elements on your own, and don't forget to resize.

**Smartphones**

Columns are defined with `.sm-*` classes.
These columns are not conditioned by any media-query and they will be displayed as default layout.

Why is there no such thing as media-query?
This is mobile-first and we will take this decision as an real advantage.

**Tablets**

For tablets there is a media-query.
So on screens that are wider than 640px, grid starts to display `.md-*` columns.

But if you don't specify the tablet columns, the grid will still use the smartphone definitions.
So use tablet columns in the cases, when you want reshape default smartphone layout.


**Gutters**

You can activate gutters by adding a `.gutters` class to <body> element or to specific `<div>` which represents one row.

Furthermore you can add `.gutter` or `.no-gutter` classes to just one column in the case you would like to gutters just for certain columns, or vice versa.  

**Offsets**

If you need to create some whitespace in the grid, you can just add `sm-offset-*` or `md-offset-*` classes to the column, needs to have a free space on the left side.


##Why to use it

GRD strives for clarity and maintainbility.

Ordnung muss sein.


##License

Feel free to click or type anywhere.
