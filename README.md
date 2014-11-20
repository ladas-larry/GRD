Singular-Grid
=============

Lightweight Mobile-first responsive CSS grid.


Made in belief, that mobile web should have it's own dedicated layout and shouldn't be mixed with bloated desktop markup and resources.



Ok, responsive webdesign is great, but it’s not a silver bullet. Moreover what happens after user shrink your responsive site on 11' laptop? Tablet version. Shouldn't be user should be free to resize browser window and still get the same desktop layout?



##How to use it


You can see sample [here](http://dharmoslap.github.io/Singular-Grid/).

**Mobile**

Columns are defined with `sm-*` classes.

As this is mobile-first grid, `sm-*` definitions are not conditioned by any media-query.

**Tablet**

For tablets there is a media-query, that triggers `md-*` definitions on screens > 640px.

**Gutters**

Each column has an optional gutter padding. You can activate gutters by the insertion of a wrapping `<p>` around the column's content.
