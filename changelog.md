# Changelog

## Version 2.0.0 (2025-06-13)

### Features

- color tokens and other internal variables are now exported and available to use

### BREAKING CHANGES

- refactored all internal values and colors
- removed *round corners* css styles `border-round`, `top-border-round`, `bottom-border-round`, `left-border-round`, `right-border-round`, `top-left-border-round`, `bottom-left-border-round`, `top-right-border-round`, `bottom-right-border-round`
    - use definition from `@css-styles/common@2.0.0`
- removed *text size* css styles `extra-extra-small-text`, `extra-small-text`, `small-text`, `medium-text`, `large-text`, `extra-large-text`, `extra-extra-large-text`, `extra-extra-extra-large-text`
    - use definition from `@css-styles/common@2.0.0`
- removed *margins, paddings, gaps*
    - use definition from `@css-styles/common@2.0.0`
- removed `popup-block` css class, no replacement
- removed `weight`s values from `defaultTheme` and css variables for `weight`s
- removed *blocks* css classes `popup-block`, `primary-block`, `secondary-block`
- removed *block variables* `--primary-*`, `--secondary-*`
- removed `primary` and `secondary` values from `defaultTheme` map
- renamed *highlight block* variables from `--block-*` to `--block-highlight-*`
- refactored *highlight block*, changed from `block` into `block.highlight` nested variable in `defaultTheme` map
- reworked buttons scss

## Version 1.0.0 (2025-03-26)

### Features

- new `css-alerts` *mixin* which generates css for alerts
- new `generate-alert` *mixin* which generates css for alerts of colours
- new `css-blocks` *mixin* which generates css for blocks
- new `css-buttons` *mixin* which generates css for buttons
- new `generate-button` *mixin* which generates css for buttons of colours
- new `css-common-components` *mixin* which generates css for overrides and styling of common components, dialog, slide toggle etc.
- new `css-common` *mixin* which generates css for common styles
- new `generate-margin-padding` *mixin* which generates css for margin and padding styles
- new `css-forms` *mixin* which generates css for forms styles
- new `css-grid` *mixin* which generates css for grid styles
- new `css-titles` *mixin* which generates css for titles styles
- new `defineTheme` *function* which gets colours from default theme
- new `buildFontFamily` *mixin* which generates css variables for font family
- new `buildBlockTheme` *mixin* which generates css variables for css blocks
- new `buildTitleTheme` *mixin* which generates css variables for css titles
- new `buildMainMenuTheme` *mixin* which generates css variables for css main menu
- new `buildDialogTheme` *mixin* which generates css variables for css dialog
- new `buildFormsTheme` *mixin* which generates css variables for css forms
- new `buildGridTheme` *mixin* which generates css variables for css grid
- new `buildMiscTheme` *mixin* which generates css variables for css misc
- new `buildAlertTheme` *mixin* which generates css variables for css alert
- new `buildTextTheme` *mixin* which generates css variables for css text
- new `buildButtonTheme` *mixin* which generates css variables for css buttons 
- new `buildMatSlideToggleTheme` *mixin* which generates css variables for css mat slide toggle
- new `buildThemeColors` *mixin* which generates css variables for all theme
