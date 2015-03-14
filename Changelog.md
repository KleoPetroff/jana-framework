# Changelog

All notable changes to this project will be documented in this file.


## 14/3/2015
### Fixed
- IE8 bug with first elements in columns grid. Removed the pseudo-classes.
- IE8 bug with dropdown being hardly accessible.
- Add `fieldset` tag in all forms, because of the text inside `legend` was outsite the tag.


## 13/3/2015
### Added
- Dropdowns for vertical and horizontal menus

### Fixed
- Fixed padding, border and box shadow bug in IE8 nad IE9 for checkboxes


## 11/3/2015 - Sanity Update
### Changes
- Project files restructured for better maintenance
- Created two main projects folders - `scss/modules` and `scss/components`
- Moved compiled css to separate css folder
- Added minified version of `styles.css`, named `styles-dist.css`


## 9/3/2015
### Added
- Navigation Dropdowns
- Navigation Disabled Buttons

### Fixed
- Fixed bug with clickable difference in navigation


## 8/3/2015
### Changes
- Moved `styles.css` to demo folder

### Added
- Horizontal and vertical menu styles and classes

### Fixed
- Removed unused js script tags on demo page


## 7/3/2015
### Changes
- Some custom typography classes with classes from the framework
- Removed unnecessary classes in demo page

### Added
- Rounded button class

### Fixed
- Removed unused link tag in demo page
- Wrong path for `styles.css` in demo page


## 5/3/2015
### Added
- Added 4 kind of table styles - Default, Bordered, Horizontal Bordered and Striped Tables

## 4/3/2015
### Changes
- Main demo font to Open Sans
- Renamed `_vars.scss` to `_variables.scss` for better clarity
- Interpolated web-fonts function font name - it will get main font name from `$main-font` variable in `_variables.scss`.

### Added
- Added typography classes
- New variables for font weight, line height, colors

### Fixed
- Bug with the grid in the demo, where the content was above 100%

## 1/3/2015
### Changes
- Moved media queries in separate file
- Updated the demo with form examples

## Added
- Added form input, textfield, legend, select, checkbox styles


## 26/2/2015
### Changes
- Updated demo index page with the new buttons and grid classes

### Added
- Added framework buttons, with several more helper buttons
- Added `.row` class wrapper
- Added `.col` grid class helper


## 25/2/2015
### Changes
- Changed the main grid wrapper from `.group` to `.col`
- Changed the name of `additional.css` to `custom-styles.css`
- Removed `utils.scss`

### Added
- Organized demo files in a separate folder
- Created custom media-queries breakpoint placeholder
- Added changelog file (duh!)

### Fixed
- Fixed some typos
- Removed unnecessary `@import`s in all scss files
