#About
Based on the well known semantic.gs by Tyler Tate, FSG (flawless-semantics-grid) shares many of the same goals that semantic.gs has. It allows for:
* column, gutter widths and the number of columns to be set; 
* switching between pixel and percentage based layouts;
* responsive and fixed layouts,
all without any unsemantic .grid_x classes in your markup. 

Check out the example pages [here](http://laughingwithu.github.com/flawless-semantics-grid/index.html).

#Differences
The most notable difference is the fact that Flawless-Semantics uses a column - gutter - column approach rather than a gutter - column - gutter approach. This solves the nesting problems I was having with Semantic.gs and also the fact that the outer most gutters where half the width of the inner gutters.

Other differences include:
* mixin to create equal height columns;
* mixin to specify the width, min-width, and max-width of a container;
* feature to allow for automatic rows and columns;
* built in vertical grid based on rythymless by [Paul GB](http://paulgb.github.com/rhythmless/);
* added a mixin to allow the grid to be visualised. This was adapted from the mixin by [Ninique](https://github.com/ninique);
* borders and padding don't affect grid;
* removal of padding as an option to be used as a gutter // this may be added in the future though it won't be implemented in the same way that it is in semantic.gs;
* support for less only at this time but this may change in the future.

#Issues
If you spot any issues or have ideas for improvement, feel free to make an issue on github or fork this project on GitHub and then issue a pull request.

#License
Licensed under Apache 2.0. // Note that this may change as I prefer the MIT licence, but have left it the same as semantic.gs for the time being.

#Created by
Flawless-Semantics was created by Sean Steindl and has been heavily influenced by a range of projects including Semantic.gs, Zen grids, Neat, Flawless, and Centage.

#Acknowledgements
The Semantic Grid System was built by [Tyler Tate](http://twitter.com/tylertate/) at [TwigKit](http://twigkit.com/) and has had various contributions by the persons listed [here](http://github.com/twigkit/semantic.gs/blob/master/changelog.md). For more see  [semantic.gs](http://github.com/twigkit/semantic.gs).
