# Changelog

## Version 2.3.0 (2025-09-05)

### Feature

 - **default theme**
    - new type of button `default`

## Version 2.2.1 (2025-09-05)

### Bug Fixes

- **default theme**
    - fixed value of `button.primary.onlyContent.foreground`, now correctly redirects to `button.primary.background`
    - fixed value of `button.primary.onlyContent.icon`, now correctly redirects to `button.primary.onlyContent.foreground`
    - fixed value of `button.success.onlyContent.foreground`, now correctly redirects to `button.success.background`
    - fixed value of `button.success.onlyContent.icon`, now correctly redirects to `button.success.onlyContent.foreground`
    - fixed value of `button.info.onlyContent.foreground`, now correctly redirects to `button.info.background`
    - fixed value of `button.info.onlyContent.icon`, now correctly redirects to `button.info.onlyContent.foreground`
    - fixed value of `button.warning.onlyContent.foreground`, now correctly redirects to `button.warning.background`
    - fixed value of `button.warning.onlyContent.icon`, now correctly redirects to `button.warning.onlyContent.foreground`
    - fixed value of `button.danger.onlyContent.foreground`, now correctly redirects to `button.danger.background`
    - fixed value of `button.danger.onlyContent.icon`, now correctly redirects to `button.danger.onlyContent.foreground`
    - fixed value of `button.primary.onlyContent.hover.background`, to `transparent`
    - fixed value of `button.primary.onlyContent.active.background`, to `transparent`
    - fixed value of `button.success.onlyContent.hover.background`, to `transparent`
    - fixed value of `button.success.onlyContent.active.background`, to `transparent`
    - fixed value of `button.info.onlyContent.hover.background`, to `transparent`
    - fixed value of `button.info.onlyContent.active.background`, to `transparent`
    - fixed value of `button.warning.onlyContent.hover.background`, to `transparent`
    - fixed value of `button.warning.onlyContent.active.background`, to `transparent`
    - fixed value of `button.danger.onlyContent.hover.background`, to `transparent`
    - fixed value of `button.danger.onlyContent.active.background`, to `transparent`

## Version 2.2.0 (2025-09-05)

### Feature

 - **default theme**
    - updated value for `theme.primary` to `$azure-500`
    - updated value for `theme.secondary` to `$blue-800`
    - updated value for `theme.tertiary` to `$orange-800`
    - updated value for `theme.success` to `$green-600`
    - updated value for `theme.info` to `$azure-500`
    - updated value for `theme.warning` to `$orange-800`
    - updated value for `theme.error` to `$red-600`
    - updated value for `theme.onPrimary` to `$white`
    - updated value for `theme.onSecondary` to `$white`
    - updated value for `theme.onTertiary` to `$white`
    - updated value for `theme.onSuccess` to `$white`
    - updated value for `theme.onInfo` to `$white`
    - updated value for `theme.onWarning` to `$white`
    - updated value for `theme.onError` to `$white`
    - updated value for `level.succes` now redirects to `theme.succes`
    - updated value for `level.info` now redirects to `theme.info`
    - updated value for `level.warning` now redirects to `theme.warning`
    - updated value for `level.error` now redirects to `theme.error`
    - updated value for `alert.info.background` now redirects to `theme.info`
    - updated value for `alert.info.foreground` now redirects to `theme.onInfo`
    - updated value for `alert.warning.background` now redirects to `theme.warning`
    - updated value for `alert.warning.foreground` now redirects to `theme.onWarning`
    - updated value for `alert.success.background` now redirects to `theme.success`
    - updated value for `alert.success.foreground` now redirects to `theme.onSuccess`
    - updated value for `alert.danger.background` now redirects to `theme.error`
    - updated value for `alert.danger.foreground` now redirects to `theme.onError`
    - updated value for `alert.error.background` now redirects to `theme.error`
    - updated value for `alert.error.foreground` now redirects to `theme.onError`
    - updated value for `text.primary.foreground` now redirects to `theme.primary`
    - updated value for `text.danger.foreground` now redirects to `theme.error`
    - updated value for `text.warning.foreground` now redirects to `theme.warning`
    - updated value for `text.success.foreground` now redirects to `theme.success`
    - updated value for `text.info.foreground` now redirects to `theme.info`
    - updated value for `button.primary.onlyContent.background` to `transparent`
    - updated value for `button.success.onlyContent.background` to `transparent`
    - updated value for `button.info.onlyContent.background` to `transparent`
    - updated value for `button.warning.onlyContent.background` to `transparent`
    - updated value for `button.danger.onlyContent.background` to `transparent`
    - updated value for `button.primary.onlyContent.foreground` now redirects to `button.primary.foreground`
    - updated value for `button.primary.onlyContent.icon` now redirects to `button.primary.icon`
    - updated value for `button.success.onlyContent.foreground` now redirects to `button.success.foreground`
    - updated value for `button.success.onlyContent.icon` now redirects to `button.success.icon`
    - updated value for `button.info.onlyContent.foreground` now redirects to `button.info.foreground`
    - updated value for `button.info.onlyContent.icon` now redirects to `button.info.icon`
    - updated value for `button.warning.onlyContent.foreground` now redirects to `button.warning.foreground`
    - updated value for `button.warning.onlyContent.icon` now redirects to `button.warning.icon`
    - updated value for `button.danger.onlyContent.foreground` now redirects to `button.danger.foreground`
    - updated value for `button.danger.onlyContent.icon` now redirects to `button.danger.icon`

## Version 2.1.0 (2025-08-25)

### Features

- new `slideInAnimation` mixin, that provides `.slide-in` css class transition (animation)
- new `slideOutAnimation` mixin, that provides `.slide-out` css class transition (animation)
- new `flyInAnimation` mixin, that provides `.fly-in` css class transition (animation)
- new `flyOutAnimation` mixin, that provides `.fly-out` css class transition (animation)
- new `fadeInAnimation` mixin, that provides `.fade-in` css class transition (animation)
- new `fadeOutAnimation` mixin, that provides `.fade-out` css class transition (animation)
- new `provideAllAnimations` mixin, that provides all available animation css classes

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
