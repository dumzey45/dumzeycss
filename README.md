# dumzeycss

**A simple, lightweight CSS utility framework** — easier than Tailwind, cleaner than Bootstrap.

Built for beginners and rapid prototyping. Write clean HTML and style it with ready-to-use utility classes.

---

## Features

- Utility-first classes (spacing, colors, flex, grid, text, borders, shadows…)
- Responsive breakpoints (`sm`, `md`, `lg` + tablet/desktop helpers)
- CSS variables for easy theming
- Tiny footprint — just one file
- No build step required
- Works with any HTML project

---

## Quick Start

### Option 1: CDN (Recommended)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dumzey45/dumzeycss@main/dumzey.css">
Option 2: Download

Download dumzey.css
Include it in your HTML:

HTML<link rel="stylesheet" href="path/to/dumzey.css">

Usage Examples
Spacing
HTML<div class="p-3 m-2">Padding + Margin</div>
<div class="padding-medium margin-large">Alternative naming</div>
Colors
HTML<div class="bg-primary text-white p-3">Primary background</div>
<p class="text-success">Success text</p>
<div class="bg-red text-white">Simple color</div>
Flexbox
HTML<div class="flex justify-between items-center">
  <div>Left</div>
  <div>Right</div>
</div>

<div class="flex flex-col items-center gap-3">
  <div>Stacked</div>
  <div>Items</div>
</div>
Grid
HTML<div class="grid grid-cols-3 gap-3">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
Typography
HTML<h1 class="text-2xl font-bold text-center">Big Title</h1>
<p class="text-sm text-secondary">Small secondary text</p>
Borders & Shadows
HTML<div class="border rounded-lg shadow-md p-4">
  Card style
</div>
Responsive
HTML<div class="flex flex-col md:flex-row">
  <!-- Column on mobile, row on medium screens and up -->
</div>

Available Utilities (Highlights)













































CategoryClassesSpacingm-0 → m-5, p-0 → p-5, mt-*, padding-*, margin-*, gap-*Colorsbg-primary, text-danger, bg-red, text-blue, etc.Flexflex, flex-col, flex-row, items-center, justify-between…Gridgrid, grid-cols-2/3/4, grid-2, grid-3…Texttext-xs → text-2xl, font-bold, text-center…Sizew-full, w-50, h-screen, h-50…Bordersrounded, rounded-lg, rounded-full, border, border-2Shadowsshadow-sm, shadow, shadow-md, shadow-lgOtheropacity-*, cursor-pointer, overflow-hidden…

Customization
Colors are defined with CSS variables. Override them in your own CSS:
CSS:root {
  --primary: #3b82f6;
  --secondary: #6b7280;
  --success: #10b981;
  --danger: #ef4444;
  --warning: #f59e0b;
  --dark: #111827;
  /* ... */
}

Browser Support
Works in all modern browsers (Chrome, Firefox, Safari, Edge).

License
MIT License © Victory Chukuwudumebie Wala

Made with ❤️ by dumzey45
