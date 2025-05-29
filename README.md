# Tailwind Ionic Utils

Tailwind CSS v4 utility library for Ionic apps. Provides dynamic utilities using the `@utility` directive.

## 📦 Installation

```bash
npm install tailwind-ionic-utils
```

## 🧩 Usage

Import into your Tailwind CSS entry file:

```css
@import "tailwind-ionic-utils/index.css";
```

> Requires Tailwind CSS v4 and a build setup that supports `@utility`.

## 🧪 Example

```html
<ion-chip class="ion-chip-bg-sky-500">
    <ion-label>Hello Ionic + Tailwind</ion-label>
</ion-chip>
```

Using utilities like `ion-chip-bg-*` allows you to define styles declaratively with utility classes — instead of inline styles like:

```html
<ion-chip style="--background: #ddd">
  <ion-label>Legacy style</ion-label>
</ion-chip>
```

This approach improves scalability and organization in design systems by promoting reusable, consistent styles.

> 🔍 For available custom properties like `--background`, `--color-selected`, and others, refer to the **CSS Custom Properties** section in the [Ionic Component Documentation](https://ionicframework.com/docs/components).

# Ionic CSS Custom Properties

This table groups all available CSS custom properties by variable and lists the components where each variable is used along with a description.

> **Note**: Refer to the [official Ionic documentation on CSS Custom Properties](https://ionicframework.com/docs/theming/css-variables) for more usage context.

## 🧩 CSS Custom Properties Table

| Variable | Used | Description | Prefix |
|----------|------|-------------|--------|
| --background | ion-action-sheet, ion-alert, ion-back-button, ion-button, ion-card, ion-chip, ion-content, ion-datetime, ion-fab-button, ion-input, ion-item, ion-item-divider, ion-item-option, ion-list-header, ion-loading, ion-menu, ion-menu-button, ion-modal, ion-popover, ion-progress-bar, ion-router-link, ion-searchbar, ion-segment, ion-segment-button, ion-select, ion-skeleton-text, ion-tab-bar, ion-tab-button, ion-textarea, ion-toast, ion-toolbar |  |  |
| --min-height | ion-action-sheet, ion-alert, ion-back-button, ion-item, ion-loading, ion-menu, ion-modal, ion-popover, ion-toast, ion-toolbar |  |  |
| --min-width | ion-action-sheet, ion-alert, ion-back-button, ion-loading, ion-menu, ion-modal, ion-popover, ion-toast |  |  |
| --height | ion-action-sheet, ion-alert, ion-loading, ion-menu, ion-modal, ion-popover, ion-range, ion-toast |  |  |
| --max-height | ion-action-sheet, ion-alert, ion-loading, ion-menu, ion-modal, ion-popover, ion-toast |  |  |
| --max-width | ion-action-sheet, ion-alert, ion-loading, ion-menu, ion-modal, ion-popover, ion-toast |  |  |
| --width | ion-action-sheet, ion-alert, ion-loading, ion-menu, ion-modal, ion-popover, ion-toast |  |  |
| --backdrop-opacity | ion-action-sheet, ion-alert, ion-loading, ion-modal, ion-popover |  |  |
| --color | ion-action-sheet, ion-back-button, ion-badge, ion-breadcrumb, ion-button, ion-card, ion-card-subtitle, ion-card-title, ion-chip, ion-content, ion-fab-button, ion-input, ion-item, ion-item-divider, ion-item-option, ion-label, ion-list-header, ion-menu-button, ion-note, ion-radio, ion-router-link, ion-searchbar, ion-segment-button, ion-spinner, ion-tab-bar, ion-tab-button, ion-textarea, ion-title, ion-toast, ion-toolbar |  |  |
| --button-color | ion-action-sheet, ion-toast |  |  |
| --border-radius | ion-avatar, ion-back-button, ion-button, ion-checkbox, ion-fab-button, ion-input, ion-item, ion-menu-button, ion-modal, ion-radio, ion-searchbar, ion-segment-button, ion-select, ion-skeleton-text, ion-textarea, ion-thumbnail, ion-toast, ion-toggle |  |  |
| --padding-top | ion-back-button, ion-badge, ion-button, ion-content, ion-fab-button, ion-input, ion-item, ion-item-divider, ion-menu-button, ion-segment-button, ion-select, ion-tab-button, ion-textarea, ion-toolbar |  |  |
| --padding-start | ion-back-button, ion-badge, ion-button, ion-content, ion-fab-button, ion-input, ion-item, ion-item-divider, ion-menu-button, ion-segment-button, ion-select, ion-tab-button, ion-textarea, ion-toolbar |  |  |
| --padding-end | ion-back-button, ion-badge, ion-button, ion-content, ion-fab-button, ion-input, ion-item, ion-item-divider, ion-menu-button, ion-segment-button, ion-select, ion-tab-button, ion-textarea, ion-toolbar |  |  |
| --padding-bottom | ion-back-button, ion-badge, ion-button, ion-content, ion-fab-button, ion-input, ion-item, ion-item-divider, ion-menu-button, ion-segment-button, ion-select, ion-tab-button, ion-textarea, ion-toolbar |  |  |
| --color-hover | ion-back-button, ion-breadcrumb, ion-button, ion-fab-button, ion-item, ion-menu-button, ion-segment-button |  |  |
| --color-focused | ion-back-button, ion-breadcrumb, ion-button, ion-fab-button, ion-item, ion-menu-button, ion-segment-button, ion-tab-button |  |  |
| --background-focused | ion-back-button, ion-breadcrumb, ion-button, ion-fab-button, ion-item, ion-menu-button, ion-segment-button, ion-tab-button |  |  |
| --transition | ion-back-button, ion-button, ion-checkbox, ion-fab-button, ion-item |  |  |
| --background-hover-opacity | ion-back-button, ion-button, ion-fab-button, ion-item, ion-menu-button, ion-segment-button |  |  |
| --background-hover | ion-back-button, ion-button, ion-fab-button, ion-item, ion-menu-button, ion-segment-button |  |  |
| --background-focused-opacity | ion-back-button, ion-button, ion-fab-button, ion-item, ion-menu-button, ion-segment-button, ion-tab-button |  |  |
| --ripple-color | ion-back-button, ion-button, ion-fab-button, ion-item, ion-select, ion-tab-button |  |  |
| --opacity | ion-back-button, ion-button, ion-toolbar |  |  |
| --margin-end | ion-back-button, ion-segment-button |  |  |
| --margin-bottom | ion-back-button, ion-segment-button |  |  |
| --margin-start | ion-back-button, ion-segment-button |  |  |
| --margin-top | ion-back-button, ion-segment-button |  |  |
| --border-width | ion-button, ion-checkbox, ion-fab-button, ion-input, ion-item, ion-list-header, ion-modal, ion-segment-button, ion-select, ion-textarea, ion-toast, ion-toolbar |  |  |
| --border-color | ion-button, ion-checkbox, ion-fab-button, ion-input, ion-item, ion-list-header, ion-modal, ion-segment-button, ion-select, ion-textarea, ion-toast, ion-toolbar |  |  |
| --border-style | ion-button, ion-checkbox, ion-fab-button, ion-input, ion-item, ion-list-header, ion-modal, ion-segment-button, ion-select, ion-textarea, ion-toast, ion-toolbar |  |  |
| --background-activated-opacity | ion-button, ion-fab-button, ion-item |  |  |
| --color-activated | ion-button, ion-fab-button, ion-item |  |  |
| --background-activated | ion-button, ion-fab-button, ion-item |  |  |
| --box-shadow | ion-button, ion-fab-button, ion-popover, ion-searchbar, ion-toast |  |  |
| --size | ion-checkbox, ion-thumbnail |  |  |
| --background-rgb | ion-datetime, ion-skeleton-text |  |  |
| --placeholder-opacity | ion-input, ion-searchbar, ion-select, ion-textarea |  |  |
| --placeholder-color | ion-input, ion-searchbar, ion-select, ion-textarea |  |  |
| --placeholder-font-style | ion-input, ion-searchbar, ion-textarea |  |  |
| --placeholder-font-weight | ion-input, ion-searchbar, ion-textarea |  |  |
| --highlight-color-focused | ion-input, ion-select, ion-textarea |  |  |
| --highlight-color-invalid | ion-input, ion-select, ion-textarea |  |  |
| --highlight-height | ion-input, ion-select, ion-textarea |  |  |
| --highlight-color-valid | ion-input, ion-select, ion-textarea |  |  |
| --inner-padding-bottom | ion-item, ion-item-divider |  |  |
| --inner-padding-top | ion-item, ion-item-divider |  |  |
| --inner-padding-start | ion-item, ion-item-divider |  |  |
| --inner-padding-end | ion-item, ion-item-divider |  |  |
| --inner-border-width | ion-item, ion-list-header |  |  |
| --color-checked | ion-radio, ion-segment-button |  |  |
| --border | ion-split-pane, ion-tab-bar |  |  |
| --button-background-selected-opacity | ion-action-sheet |  |  |
| --button-color-disabled | ion-action-sheet |  |  |
| --button-color-focused | ion-action-sheet |  |  |
| --button-color-hover | ion-action-sheet |  |  |
| --button-color-selected | ion-action-sheet |  |  |
| --button-background-selected | ion-action-sheet |  |  |
| --button-background-hover-opacity | ion-action-sheet |  |  |
| --button-background | ion-action-sheet |  |  |
| --button-background-activated | ion-action-sheet |  |  |
| --button-background-activated-opacity | ion-action-sheet |  |  |
| --button-background-focused | ion-action-sheet |  |  |
| --button-background-focused-opacity | ion-action-sheet |  |  |
| --button-color-activated | ion-action-sheet |  |  |
| --button-background-hover | ion-action-sheet |  |  |
| --icon-padding-top | ion-back-button |  |  |
| --icon-margin-end | ion-back-button |  |  |
| --icon-margin-start | ion-back-button |  |  |
| --icon-margin-top | ion-back-button |  |  |
| --icon-padding-bottom | ion-back-button |  |  |
| --icon-padding-end | ion-back-button |  |  |
| --icon-padding-start | ion-back-button |  |  |
| --icon-font-size | ion-back-button |  |  |
| --icon-font-weight | ion-back-button |  |  |
| --icon-margin-bottom | ion-back-button |  |  |
| --color-active | ion-breadcrumb |  |  |
| --checkmark-width | ion-checkbox |  |  |
| --checkmark-color | ion-checkbox |  |  |
| --checkbox-background-checked | ion-checkbox |  |  |
| --checkbox-background | ion-checkbox |  |  |
| --border-color-checked | ion-checkbox |  |  |
| --ion-grid-column-padding | ion-col |  |  |
| --ion-grid-column-padding-lg | ion-col |  |  |
| --ion-grid-column-padding-md | ion-col |  |  |
| --ion-grid-column-padding-sm | ion-col |  |  |
| --ion-grid-column-padding-xl | ion-col |  |  |
| --ion-grid-column-padding-xs | ion-col |  |  |
| --ion-grid-columns | ion-col |  |  |
| --offset-top | ion-content |  |  |
| --keyboard-offset | ion-content |  |  |
| --offset-bottom | ion-content |  |  |
| --wheel-fade-background-rgb | ion-datetime |  |  |
| --title-color | ion-datetime |  |  |
| --wheel-highlight-background | ion-datetime |  |  |
| --wheel-highlight-border-radius | ion-datetime |  |  |
| --close-icon-font-size | ion-fab-button |  |  |
| --ion-grid-padding-sm | ion-grid |  |  |
| --ion-grid-padding-lg | ion-grid |  |  |
| --ion-grid-padding-md | ion-grid |  |  |
| --ion-grid-padding-xl | ion-grid |  |  |
| --ion-grid-padding-xs | ion-grid |  |  |
| --ion-grid-width | ion-grid |  |  |
| --ion-grid-width-lg | ion-grid |  |  |
| --ion-grid-width-md | ion-grid |  |  |
| --ion-grid-width-sm | ion-grid |  |  |
| --ion-grid-width-xl | ion-grid |  |  |
| --ion-grid-width-xs | ion-grid |  |  |
| --ion-grid-padding | ion-grid |  |  |
| --inner-box-shadow | ion-item |  |  |
| --detail-icon-color | ion-item |  |  |
| --detail-icon-font-size | ion-item |  |  |
| --detail-icon-opacity | ion-item |  |  |
| --spinner-color | ion-loading |  |  |
| --fade-background-rgb | ion-picker |  |  |
| --highlight-background | ion-picker |  |  |
| --highlight-border-radius | ion-picker |  |  |
| --offset-x | ion-popover |  |  |
| --offset-y | ion-popover |  |  |
| --progress-background | ion-progress-bar |  |  |
| --inner-border-radius | ion-radio |  |  |
| --bar-background-active | ion-range |  |  |
| --knob-background | ion-range |  |  |
| --pin-color | ion-range |  |  |
| --pin-background | ion-range |  |  |
| --bar-background | ion-range |  |  |
| --knob-size | ion-range |  |  |
| --knob-box-shadow | ion-range |  |  |
| --knob-border-radius | ion-range |  |  |
| --bar-border-radius | ion-range |  |  |
| --bar-height | ion-range |  |  |
| --icon-color | ion-searchbar |  |  |
| --clear-button-color | ion-searchbar |  |  |
| --cancel-button-color | ion-searchbar |  |  |
| --indicator-box-shadow | ion-segment-button |  |  |
| --indicator-height | ion-segment-button |  |  |
| --indicator-transform | ion-segment-button |  |  |
| --indicator-transition | ion-segment-button |  |  |
| --background-checked | ion-segment-button |  |  |
| --indicator-color | ion-segment-button |  |  |
| --side-max-width | ion-split-pane |  |  |
| --side-width | ion-split-pane |  |  |
| --side-min-width | ion-split-pane |  |  |
| --color-selected | ion-tab-button |  |  |
| --white-space | ion-toast |  |  |
| --end | ion-toast |  |  |
| --start | ion-toast |  |  |
| --handle-width | ion-toggle |  |  |
| --handle-box-shadow | ion-toggle |  |  |
| --handle-height | ion-toggle |  |  |
| --track-background | ion-toggle |  |  |
| --track-background-checked | ion-toggle |  |  |
| --handle-spacing | ion-toggle |  |  |
| --handle-max-height | ion-toggle |  |  |
| --handle-background | ion-toggle |  |  |
| --handle-background-checked | ion-toggle |  |  |
| --handle-border-radius | ion-toggle |  |  |
| --handle-transition | ion-toggle |  |  |

---

✅ This structure improves maintainability and provides an overview for developers looking to style Ionic components consistently.

Feel free to extend this file as you extract more variables from additional components!

## 🚀 Build & Publish

```bash
npm run build

# Publish alpha release
npm run publish:alpha

# Publish beta release
npm run publish:beta

# Publish stable patch release
npm run publish:stable
```
