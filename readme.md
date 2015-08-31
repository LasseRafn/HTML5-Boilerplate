#HTML5 Boilerplate
This project is intended for my own projects, but feel free to use if you wish.

## Vendors:
* jquery/jquery (2.1.4)
* aFarkas/HTML5Shiv (3.7.3)
* scottjehl/Respond (1.4.2)
* necolas/Normalize.css (3.0.3) - __Modified: removed hgroup.__

## Todo:
* Add Gruntfile for compiling JS and SASS (Issue: Create versioning (X.X.X) on file: app.0.5.1.min.js)

## Bem Instructions
* Elements are written as such: 

    .block
    .site-header

* Sub elements (A children of a element) are written as such:

    .block
        .block__header

Or if you prefer not to use nesting:

    .block
    .block__header

* Element modifiers are written as such:

    .block
        &.block--large

or if you prefer not to use nesting:

    .block
    .block--large

* Global styles (example: .input-field) should NOT use BEM
* Nesting should be used appropriately, to ensure dynamic code.
