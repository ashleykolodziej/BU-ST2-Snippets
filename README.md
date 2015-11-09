# BU-ST2-Snippets
A collection of snippets for Sublime Text 2 to speed up development for cmb2, Wordpress, and SASS. Among the goodies:

* Some standard CSS nonsense
* cmb2 snippets for easier metaboxes
* Some standard Wordpress functions to make your life easier

## To install:

Clone this repository as usual, but instead of cloning to your normal development folder, clone to the Sublime Text 2 Packages folder:

**Mac users:** `/Users/YOURUSERNAME/Library/Application Support/Sublime Text 2/Packages`

Don't see the Library folder? [Here's how you fix that.](http://www.macworld.com/article/2057221/how-to-view-the-library-folder-in-mavericks.html)

When you start typing certain keywords in certain files, such as "addNewShortcode", you'll now see Sublime bring up the autocomplete menu with that keyword. Hit tab, and the snippet will complete for you, pre-highlighting any information you might want to change. Hit tab to cycle through all the information the snippet is set up to change for you.

## Currently supported snippets:

### CSS/SASS files

* `arrowDown`: creates a CSS arrow pointing down using `:before`
* `arrowLeft`: creates a CSS arrow pointing left using `:before`
* `arrowRight`: creates a CSS arrow pointing right using `:before`
* `arrowUp`: creates a CSS arrow pointing up using `:before`

#### Responsive Framework (BU Only)

##### Grids

* `grid-Half`: Writes the base `@extend` rule to create a grid of half width in Responsive.
* `grid-Third`: Writes the base `@extend` rule to create a grid of third width in Responsive.
* `grid-Quarter`: Writes the base `@extend` rule to create a grid of quarter width in Responsive.
* `grid-twoThird`: Writes the base `@extend` rule to create a grid of two thirds width in Responsive.
* `grid-threeQuarter`: Writes the base `@extend` rule to create a grid of three quarter width in Responsive.
* `gridCustom`: Writes the base `@extend` rule to create a grid of any width in Responsive. # = number of columns out of 12

##### Mixins

* `animation`: Writes the base `@include` rule for the animation mixin.
* `keyframes`: Writes the base `@include` rule for the keyframes mixin.
* `borderRadius`: Writes the base `@include` rule for the border radius mixin.
* `boxShadow`: Writes the base `@include` rule for the box shadow mixin.
* `breakpoint`: Writes the base `@include` rule for the breakpoint mixin.
* `clearfix`: Writes the base `@extend` rule for clearfixes.
* `gradient`: Writes the base `@include` rule for the gradient mixin.
* `opacity`: Writes the base `@include` rule for the opacity mixin.
* `rgba`: Writes the base `@include` rule for the rgba-color mixin.
* `rotate`: Writes the base `@include` rule for the rotate mixin.
* `scale`: Writes the base `@include` rule for the scale mixin.
* `transition`: Writes the base `@include` rule for the transition mixin.
* `translate`: Writes the base `@include` rule for the translate mixin.

### PHP files

#### cmb2

* `cmb2-AddMetabox`: A skeleton function for adding metaboxes using cmb2.
* `cmb2-AddField`: A skeleton for adding fields to a metabox using cmb2. Use inside the skeleton addMetabox function. Supported field types are as follows:
	* `checkbox`
	* `code`
	* `colorpicker`
	* `email`
	* `file`
	* `group`
	* `linkpicker` (BU only)
	* `radio`
	* `select`
	* `text`
	* `textSmall`
	* `textMedium`
	* `textarea`
	* `time`
	* `title`
	* `wysiwyg`

Only the most commonly used cmb2 fields have snippets written here - cmb2 does support other fields. Please refer to their documentation if you don't find what you need here.

#### Wordpress

* `adminCSS`: Skeleton function to add a custom CSS stylesheet to the Wordpress admin.
* `newPostType`: Skeleton function to add a custom post type to Wordpress.
* `newShortcode`: Skeleton function to add a new shortcode to Wordpress.
* `newSidebar`: Skeleton function to add a new sidebar to Wordpress.