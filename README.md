GRD
=============



Made in belief, that mobile web should have it's own dedicated layout and shouldn't be mixed with bloated desktop markup and resources.

Ok, responsive webdesign is great, but it’s not a silver bullet.

Moreover what happens after user shrink your responsive site on 11' laptop?
Tablet version. Shouldn't be user free to resize browser window and still get the same desktop layout?



##How to use it


You can find a sample [here](http://dharmoslap.github.io/Singular-Grid/).

###Smartphones

Columns are defined with `.sm-*` classes.
These columns are not conditioned by any media-query.
So these columns will be displayed as default layout.

Why is there no such thing as media-query?
This is mobile-first and we will take this decision as an real advantage.

###Tablets

For tablets there is a media-query.
So on screens that are wider than 640px, grid starts to display `.md-*` columns.

But if you don't specify the tablet columns, the grid will still use the smartphone definitions.
So use `.md-*` classes for the cases, when you want reshape default smartphone layout.


###Gutters

You can activate gutters by adding a `.gutters` class to <body> element or to specific `<div>` which represents one row.

Furthermore you can add `.gutter` or `.no-gutter` classes to just one column in the case you would like to gutters just for certain columns, or vice versa.  


##Why to use it?

GRD strives for clarity, maintainbility and compatibility.

Ordnung muss sein!


##License

Feel free to click or type anywhere.
