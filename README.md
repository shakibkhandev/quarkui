# QuarkUI

A lightweight, modern CSS framework for building responsive web applications.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
  - [CDN](#cdn)
  - [NPM](#npm)
- [Components](#components)
  - [Grid System](#grid-system)
  - [Buttons](#buttons)
  - [Cards](#cards)
  - [Alerts](#alerts)
- [Utility Classes](#utility-classes)
  - [Spacing](#spacing)
  - [Typography](#typography)
  - [Display](#display)
  - [Colors](#colors)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

---

## Features

✨ QuarkUI comes packed with:

- 🎨 Modern, clean design system
- 📱 Mobile-first responsive grid system
- 🎯 Utility-first approach
- 🧩 Common UI components
- 🎭 Customizable theme using CSS variables
- 🚀 Zero dependencies
- 📦 Small footprint

---

## Installation

### CDN

Add the following link tag in your HTML file's `<head>` section:

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/quarkui@1.0.0/dist/styles.css"
/>
```

### NPM

Install via npm:

```bash
npm install quarkui
```

Import in your JavaScript file:

```javascript
import "quarkui/dist/styles.css";
```

---

## Components

### Grid System

QuarkUI includes a flexible 12-column grid system based on flexbox:

```html
<div class="container">
  <div class="row">
    <div class="col-6">Half width column</div>
    <div class="col-6">Half width column</div>
  </div>
</div>
```

### Buttons

Various button styles for different actions:

```html
<!-- Button variations -->
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-success">Success</button>
<button class="btn btn-danger">Danger</button>
```

### Cards

Flexible card components for content containers:

```html
<!-- Basic card structure -->
<div class="card">
  <div class="card-header">Card Header</div>
  <div class="card-body">
    <h5>Card Title</h5>
    <p>Card content goes here.</p>
    <button class="btn btn-primary">Action</button>
  </div>
</div>
```

### Alerts

Contextual feedback messages:

```html
<!-- Alert examples -->
<div class="alert alert-primary">Primary alert message</div>
<div class="alert alert-danger">Danger alert message</div>
```

---

## Utility Classes

### Spacing

Consistent spacing utilities for margin and padding:

| Class      | Description         |
| ---------- | ------------------- |
| `m-[0-5]`  | Margin (all sides)  |
| `mt-[0-5]` | Margin top          |
| `mb-[0-5]` | Margin bottom       |
| `p-[0-5]`  | Padding (all sides) |
| `pt-[0-5]` | Padding top         |
| `pb-[0-5]` | Padding bottom      |

### Typography

Text formatting utilities:

```html
<!-- Typography examples -->
<p class="text-center">Centered text</p>
<p class="text-primary">Primary colored text</p>
<p class="text-bold">Bold text</p>
<p class="text-italic">Italic text</p>
```

### Display

Flexible display utilities:

```html
<!-- Display utilities -->
<div class="d-flex justify-content-between align-items-center">
  <div>Flex item 1</div>
  <div>Flex item 2</div>
</div>

<div class="d-grid gap-2">
  <div>Grid item 1</div>
  <div>Grid item 2</div>
</div>
```

### Colors

Background and text color utilities:

```html
<!-- Color utilities -->
<div class="bg-primary text-light">Primary background</div>
<div class="bg-success text-light">Success background</div>
<div class="text-primary">Primary text</div>
<div class="text-success">Success text</div>
```

---

## Customization

QuarkUI uses CSS variables for easy customization. Override these variables in your CSS:

```css
:root {
  /* Colors */
  --primary: #your-color;
  --secondary: #your-color;
  --success: #your-color;
  --danger: #your-color;
  --warning: #your-color;
  --info: #your-color;
  --light: #your-color;
  --dark: #your-color;

  /* Typography */
  --font-family: your-font-stack;
  --font-size-base: your-size;
  --line-height-base: your-line-height;

  /* Layout */
  --spacing-unit: your-spacing;
  --container-padding: your-padding;
  --border-radius: your-radius;
}
```

---

## Browser Support

QuarkUI supports all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

MIT License - feel free to use this framework in your projects.
#   q u a r k u i 
 
 
