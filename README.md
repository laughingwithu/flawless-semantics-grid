#About
Based on the well known semantic.gs by Tyler Tate, Flawless-Semantics shares many of the same goals that semantic.gs has. It allows for:
* column, gutter widths and the number of columns to be set; 
* switching between pixel and percentage based layouts;
* responsive fixed alayouts,
all without any unsemantic .grid_x classes in your markup. 

Flawless-Semantics was originally built to address several issues that I had with semantic.gs and while some of the changes were compatible with that project, several changes resulted in a grid which was not compatible with semantic.gs. I will continue to contribute to semantic.gs and will work to get both of these aproaches compatible with each other.

#Differences
The most notable difference is the fact that Flawless-Semantics uses a column - gutter - column approach rather than a gutter - column - approach. This solves the nesting problems I was having with Semantic.gs and also the fact that the outer most gutters where half the width of the inner gutters.

Other differences include:
* mixin to create equal height columns;
* mixin to specify the width, min-width, and max-width of a container;
* modification of .column mixin to allow for an omega attribute;
* feature to allow for automatic rows and columns;
* removal of padding as an option to be used as a gutter // this may be added in the future though it won't be implemented the same way that it is in semantic.gs;
* support for less only at this time but this may change in the future.

#Issues
If you spot any issues or have ideas for improvement, feel free to make an issue on github or fork this project on GitHub and then issue a pull request.

#License
Licensed under Apache 2.0. // Note that this may change as I prefer the MIT licence, but have left it the same as semantic.gs for the time being.

#Created by
Flawless-Semantics was created by Sean Steindl and has been heavily influenced by a range of projects including Semantic.gs, Zen grids, Neat, Flawless, and Centage.

#Acknowledgements
The Semantic Grid System was built by [Tyler Tate](http://twitter.com/tylertate/) at [TwigKit](http://twigkit.com/) and has had various contributions. For more see  [semantic.gs](http://github.com/twigkit/semantic.gs).