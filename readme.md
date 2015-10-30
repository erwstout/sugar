## SUGAR!!!
A pretty sweet Sass Mixin Library.

Using Sugar is pretty straight forward. Copy the .scss file into your directory and include it in your .scss file and that's it. You're done. 

OR:

Install using Bower.
`$ bower install sugar-mixins`

##Updates
* 10/29/15 - Creates a bower package.
* 9/16/15 - Added a center mixin to horizontally and vertically center elements.
* 6/08/15 - Added column count mixin to easily add CSS3 column counts to paragraphs.
* 6/03/15 - Added placeholder mixin for easy styling of form placeholder text.
* 4/20/15 - Added column count mixin.
* 4/14/15 - Added new mixin for background size. Simply use `@include background-size($bgsize)` to declare the background size. Does not replace `@include background-cover`. 

##List of Current Mixins

```
#!sass

@include background-cover
@include background-size($bgsize)
@include border-radius ($radius)
@include transition($speed)
@include box-shadow($box-shadow)
@include column-count($count)
@include placeholder{ your styles }
@include col-count($cols)
@include centerer
```
