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

Available classes:

* `u-inline` - Display inline.
* `u-inlineBlock` - Display inline-block.
* `u-block` - Display block.
* `u-table` - Display table.
* `u-tableCell` - Display table-cell.


## _layout.scss

Available classes:

* `u-cf` - Contain floats (micro clearfix).
* `u-nbfc` - Create a new block formatting context.
* `u-nbfcAlt` - Create a new block formatting context (alternative technique).
* `u-pullLeft` - Float left.
* `u-pullRight` - Float right.


## _link.scss

Available classes:

* `u-linkBlock` - Block-level link with no `text-decoration` for any state.

* `u-linkClean` - A link without no `text-decoration` for any state.

* `u-linkComplex` - Limit a link's interactive `text-decoration` underline to a
  sub-section of the link text.

    ```html
    <a class="u-linkComplex" href="{url}">
      Link complex
      <span class="u-linkComplexTarget">target</span>
    </a>
    ```

* `u-linkPseudo` - Make another interactive element, e.g., `button`, look like
  a link.

    ```html
    <button class="u-linkPseudo" type="button">
      Link-like button
    </button>
    ```

variables are set with !default

* `$color-linkPseudo`: the text color to use for `button` when styled like a text link.
* `$color-hover-linkPseudo`: the text interaction color to use for `button` when styled like a text link.


## _offset.scss 

  A convenient way to import both _before.scss and _after.scss


## _before.scss

Available classes

* `u-beforeXofY` (numerous) - Specify the proportional offset before an object.

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12.

### Plugins

Utilities that can be limited to specific Media Query breakpoints.

* `u-sm-beforeXofY` - To use at the small Media Query breakpoint.
* `u-md-beforeXofY` - To use at the medium Media Query breakpoint.
* `u-lg-beforeXofY` - To use at the large Media Query breakpoint.


## _after.scss 

 Available classes

* `u-afterXofY` (numerous) - Specify the proportional offset before an object.

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12.

### Plugins

Utilities that can be limited to specific Media Query breakpoints.

* `u-sm-afterXofY` - To use at the smallest Media Query breakpoint.
* `u-md-afterXofY` - To use at the medium Media Query breakpoint.
* `u-lg-afterXofY` - To use at the large Media Query breakpoint.


## __size.scss

Available classes

* `u-sizeFit` - Make an element shrink wrap its content by floating left.
* `u-sizeFitAlt` - Make an element shrink wrap its content by floating right.
* `u-sizeFill` - Make an element fill the remaining space.
* `u-sizeFillAlt` - An alternative method to make an element fill the remaining space.
* `u-sizeFull` - Make an element the width of its parent.
* `u-sizeXofY` (numerous) - Specify the proportional width of an object.

`X` must be an integer less than `Y`.

`Y` can be any of the following numbers: 2, 3, 4, 5, 6, 8, 10, 12.

### Plugins

Utilities that can be limited to specific Media Query breakpoints.

* `u-sm-sizeXofY` - To use at the smallest Media Query breakpoint.
* `u-md-sizeXofY` - To use at the medium Media Query breakpoint.
* `u-lg-sizeXofY` - To use at the largest Media Query breakpoint.


