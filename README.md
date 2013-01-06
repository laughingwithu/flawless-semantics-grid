#About
Based on the well known semantic.gs by Tyler Tate this grid system shares many of the same goals that semantic.gs has. It allows for:
1. column, gutter widths and the number of columns to be set, 
2. switching between pixels and percentage based layouts
3. responsive fixed alayouts, 
all without any unsemantic .grid_x classes in your markup. 

This Grid system was built originally to address several issues that I had with semantic.gs and while some of the changes were compatible with that project, several changes resulted in a grid which behaves rather differently and is not backwards compatible with the semantic.gs. I will continue to contribute to semantic.gs and will work to get both of these aproaches compatible with each other.

#Differences
The most notable difference is the fact that this grid system uses a column - gutter - column approach rather than a gutter - column - approach. This solves for me the nesting problems I was having with Semantic.gs and also the fact that the outer most gutters where half the width of the inner gutters.

Other differences include:
1. mixin to create equal height columns
2. mixin to specify the width, min-width, and max-width of a container
3. modification of .column mixin to allow for an omega attribute
4. feature to allow for automatic rows and columns
5. removal of padding as an option to be used as a gutter // this may be added in the future though it won't be implemented the same way that it is in semantic.gs
6. support for less only at this time but this may change in the future.

#Issues
If you spot any issues or have ideas for improvement, feel free to make an issue on github or fork this project on GitHub and then issue a pull request.

#License
Licensed under Apache 2.0. // Note that this may change as I prefer the MIT licence, but have left it the same as semantic.gs for the time being.

#Created by
This Grid system was created by Sean Steindl and has been heavily influenced by a range of projects including Semantic.gs, Zen grids, Neat, Flawless, and Centage.

#Acknowledgements
The Semantic Grid System was built by [Tyler Tate](http://twitter.com/tylertate/) at [TwigKit](http://twigkit.com/) and has had various contributions. For more see the [project](http://github.com/twigkit/semantic.gs).
