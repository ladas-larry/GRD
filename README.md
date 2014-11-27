GRD
=============

Lightweight Mobile-first CSS grid.


Made in belief, that mobile web should have it's own dedicated layout and shouldn't be mixed with bloated desktop markup and resources.



Ok, responsive webdesign is great, but it’s not a silver bullet. Moreover what happens after user shrink your responsive site on 11' laptop? Tablet version. Shouldn't be user should be free to resize browser window and still get the same desktop layout?



##How to use it


You can see sample [here](http://dharmoslap.github.io/Singular-Grid/).

**Mobile**

Columns are defined with `.sm-*` classes.

As this is mobile-first grid, `.sm-*` definitions are not conditioned by any media-query.

**Tablet**

For tablets there is a media-query, that triggers `.md-*` definitions on screens > 640px.

**Gutters**

You can activate gutters by adding a `.gutters` class to <body> element or to specific `<div>` which represents one row.

Furthermore you can add `.gutter` or `.no-gutter` classes to just one column in the case you would like to gutters just for certain columns, or vice versa.  
