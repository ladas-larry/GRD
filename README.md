Singular-Grid
=============

Lightweight Mobile-first responsive CSS grid. 


Made in belief, that mobile web should have it's own dedicated layout and shouldn't be mixed with bloated desktop markup and resources. 



Ok, responsive webdesign is great, but it’s not a silver bullet. Moreover what happens after user shrink your responsive web on 11' laptop? Tablet version? Shouldn't be user should be free to resize browser window and still get the same desktop layout? 



##How to use it


You can see sample [here](http://dharmoslap.github.io/Singular-Grid/). 


Columns are defined with `sm-*` classes, and as this is mobile-first grid, `sm-*` definitions are not conditioned by any media-query. 

For tablets there a media-query, that triggers `md-*` definitions on screens > 640px.

There are also optional gutters, tht can be defined for `[class*=sm]` and `[class*=md]` selectors.



