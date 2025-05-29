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
