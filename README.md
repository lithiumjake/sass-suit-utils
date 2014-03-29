# SASS-SUIT-UTILS

Base.css and all of the SUIT utilities respectfully ported from CSS4 to SASS modules

## SUIT

SUIT is an HTML/CSS framework for creating loosely coupled UI components, 
originally created by Nicolas Gallagher

SUIT also provides a collection of small, adaptive, structural HTML/CSS modules
built using a naming convention inspired by the BEM methodology.

Learn more about SUIT and the utilities it provides at https://github.com/suitcss/suit

## _base.scss

Base styles for web applications. Provides a thin layer on top of
[Normalize.css](https://github.com/necolas/normalize.css). Removes default
margins and exposes variables for theming.

#### Configurable variables

The following variables are set with !default

* `$background-base`: the application background style.
* `$color-base`: the root text color.
* `$font-base`: the root font style.
* `$link-color-base`: the root link color.
* `$link-color-hover-base`: the root link interaction (`:hover`, `:focus`,
  `:active`) color.

## _all.scss

A convenient way to include all SASS-SUIT utility modules


## _display.scss

* `u-inline` - Display inline.
* `u-inlineBlock` - Display inline-block.
* `u-block` - Display block.
* `u-table` - Display table.
* `u-tableCell` - Display table-cell.
* 
