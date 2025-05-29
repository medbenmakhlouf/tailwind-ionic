# Tailwind Ionic Utils

Tailwind CSS v4 utility library for Ionic apps. Provides dynamic utilities using the `@utility` directive.

## 📦 Installation

```bash
npm install tailwind-ionic
```

## 🧩 Usage

Import into your Tailwind CSS entry file:

```css
@import "tailwind-ionic/index.css";
```

> Requires Tailwind CSS v4 and a build setup that supports `@utility`.

## 🧪 Example

```html
<ion-chip class="ion-chip-bg-sky-500">
  <ion-label>Hello Ionic + Tailwind</ion-label>
</ion-chip>
```

## 🚀 Build & Publish

```bash
npm run build
npm run publish:public
```