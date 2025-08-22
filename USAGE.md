# GlacierCSS Usage Guide

Quick reference for using GlacierCSS in your projects.

## 🚀 Quick Start

### Installation
```bash
npm install glaciercss
```

### CDN
```html
<link href="https://cdn.jsdelivr.net/npm/glaciercss@1.0.0/dist/glaciercss.min.css" rel="stylesheet">
```

### Basic HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
    <link rel="stylesheet" href="glaciercss.min.css">
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-12 col-md-6">
                <div class="card">
                    <div class="card-body">
                        <h4 class="card-title">Hello World</h4>
                        <p class="card-text">This is a responsive card!</p>
                        <button class="btn btn-primary">Get Started</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
```

## 🏗️ Grid System

### Container
```html
<div class="container">Fixed width container</div>
<div class="container-fluid">Full width container</div>
```

### Row & Columns
```html
<div class="row">
    <div class="col-12">Full width (mobile)</div>
    <div class="col-12 col-md-6">Half width (tablet+)</div>
    <div class="col-12 col-md-6 col-lg-4">Third width (desktop+)</div>
</div>
```

### Column Sizes
- `.col-1` through `.col-12` - Fixed column widths
- `.col-auto` - Auto-sizing column
- `.col` - Flexible column

### Responsive Grid Examples
```html
<!-- Mobile: Full width, Desktop: Half width -->
<div class="col-12 col-lg-6">Content</div>

<!-- Mobile: Full width, Tablet: Half width, Desktop: Third width -->
<div class="col-12 col-md-6 col-lg-4">Content</div>

<!-- Mobile: Full width, Small: Half width, Large: Quarter width -->
<div class="col-12 col-sm-6 col-lg-3">Content</div>
```

### Grid Utilities
```html
<div class="row no-gutters">No spacing between columns</div>
<div class="row gutters-sm">Small spacing between columns</div>
<div class="row gutters-lg">Large spacing between columns</div>
```

## 🎨 Components

### Buttons
```html
<!-- Button Variants -->
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-success">Success</button>
<button class="btn btn-warning">Warning</button>
<button class="btn btn-danger">Danger</button>
<button class="btn btn-info">Info</button>
<button class="btn btn-light">Light</button>
<button class="btn btn-dark">Dark</button>

<!-- Button Styles -->
<button class="btn btn-outline-primary">Outline</button>
<button class="btn btn-ghost-primary">Ghost</button>

<!-- Button Sizes -->
<button class="btn btn-primary btn-sm">Small</button>
<button class="btn btn-primary">Default</button>
<button class="btn btn-primary btn-lg">Large</button>
<button class="btn btn-primary btn-xl">Extra Large</button>

<!-- Button States -->
<button class="btn btn-primary btn-block">Block Button</button>
<button class="btn btn-primary loading">Loading...</button>
```

### Cards
```html
<!-- Basic Card -->
<div class="card">
    <div class="card-header">
        <h4 class="card-title">Card Title</h4>
        <p class="card-subtitle">Card subtitle</p>
    </div>
    <div class="card-body">
        <p class="card-text">Card content goes here.</p>
        <button class="btn btn-primary">Action</button>
    </div>
    <div class="card-footer">
        <small class="text-muted">Footer content</small>
    </div>
</div>

<!-- Card Variants -->
<div class="card card-borderless">No border</div>
<div class="card card-elevated">With shadow</div>
<div class="card card-interactive">Clickable</div>
<div class="card card-primary">Primary themed</div>

<!-- Card with Image -->
<div class="card">
    <img src="image.jpg" class="card-img-top" alt="Card image">
    <div class="card-body">
        <h4 class="card-title">Card with Image</h4>
        <p class="card-text">Image card content.</p>
    </div>
</div>

<!-- Card Effects -->
<div class="card hover-lift">Hover lift effect</div>
<div class="card hover-scale">Hover scale effect</div>
<div class="card hover-glow">Hover glow effect</div>
```

## 🎯 Utility Classes

### Spacing (Margin & Padding)
```html
<!-- Margin -->
<div class="m-0">No margin</div>
<div class="m-1">Small margin</div>
<div class="m-2">Medium margin</div>
<div class="m-3">Large margin</div>
<div class="m-4">Extra large margin</div>
<div class="m-5">Huge margin</div>
<div class="m-6">Massive margin</div>
<div class="m-8">Giant margin</div>

<!-- Directional Margin -->
<div class="mt-4">Top margin</div>
<div class="mr-4">Right margin</div>
<div class="mb-4">Bottom margin</div>
<div class="ml-4">Left margin</div>
<div class="mx-4">Horizontal margin</div>
<div class="my-4">Vertical margin</div>

<!-- Padding (same pattern) -->
<div class="p-4">Padding all sides</div>
<div class="pt-4">Top padding</div>
<div class="px-4">Horizontal padding</div>
<div class="py-4">Vertical padding</div>

<!-- Responsive Spacing -->
<div class="p-2 p-md-4 p-lg-6">Responsive padding</div>
<div class="m-2 m-md-4 m-lg-6">Responsive margin</div>
```

### Display & Layout
```html
<!-- Display -->
<div class="d-block">Block display</div>
<div class="d-inline">Inline display</div>
<div class="d-inline-block">Inline block</div>
<div class="d-flex">Flexbox display</div>
<div class="d-inline-flex">Inline flexbox</div>
<div class="d-none">Hidden</div>

<!-- Responsive Display -->
<div class="d-none d-md-block">Hidden on mobile, visible on tablet+</div>
<div class="d-block d-lg-none">Visible on mobile, hidden on desktop</div>

<!-- Flexbox -->
<div class="d-flex justify-content-center align-items-center">Centered flexbox</div>
<div class="d-flex justify-content-between">Space between items</div>
<div class="d-flex justify-content-around">Space around items</div>
<div class="d-flex flex-column">Vertical flexbox</div>
<div class="d-flex flex-wrap">Wrapping flexbox</div>
```

### Text Utilities
```html
<!-- Text Sizes -->
<p class="text-xs">Extra small text</p>
<p class="text-sm">Small text</p>
<p class="text-base">Base text</p>
<p class="text-lg">Large text</p>
<p class="text-xl">Extra large text</p>
<p class="text-2xl">2XL text</p>
<p class="text-3xl">3XL text</p>
<p class="text-4xl">4XL text</p>
<p class="text-5xl">5XL text</p>

<!-- Font Weights -->
<p class="font-light">Light weight</p>
<p class="font-normal">Normal weight</p>
<p class="font-medium">Medium weight</p>
<p class="font-semibold">Semibold weight</p>
<p class="font-bold">Bold weight</p>
<p class="font-extrabold">Extra bold weight</p>

<!-- Text Alignment -->
<p class="text-left">Left aligned</p>
<p class="text-center">Center aligned</p>
<p class="text-right">Right aligned</p>
<p class="text-justify">Justified text</p>

<!-- Responsive Text Alignment -->
<p class="text-center text-md-left text-lg-center">Responsive alignment</p>

<!-- Text Utilities -->
<p class="text-truncate">Truncated text with ellipsis...</p>
<p class="text-break">Break long words</p>
<p class="uppercase">UPPERCASE TEXT</p>
<p class="lowercase">lowercase text</p>
<p class="capitalize">Capitalized Text</p>
<p class="underline">Underlined text</p>
```

### Colors
```html
<!-- Text Colors -->
<p class="text-primary">Primary text</p>
<p class="text-secondary">Secondary text</p>
<p class="text-success">Success text</p>
<p class="text-warning">Warning text</p>
<p class="text-danger">Danger text</p>
<p class="text-info">Info text</p>
<p class="text-muted">Muted text</p>
<p class="text-light">Light text</p>
<p class="text-dark">Dark text</p>

<!-- Background Colors -->
<div class="bg-primary">Primary background</div>
<div class="bg-secondary">Secondary background</div>
<div class="bg-success">Success background</div>
<div class="bg-warning">Warning background</div>
<div class="bg-danger">Danger background</div>
<div class="bg-info">Info background</div>
<div class="bg-light">Light background</div>
<div class="bg-dark">Dark background</div>
<div class="bg-white">White background</div>
```

### Position & Layout
```html
<!-- Position -->
<div class="position-static">Static positioning</div>
<div class="position-relative">Relative positioning</div>
<div class="position-absolute">Absolute positioning</div>
<div class="position-fixed">Fixed positioning</div>
<div class="position-sticky">Sticky positioning</div>

<!-- Float -->
<div class="float-left">Float left</div>
<div class="float-right">Float right</div>
<div class="float-none">No float</div>

<!-- Overflow -->
<div class="overflow-auto">Auto overflow</div>
<div class="overflow-hidden">Hidden overflow</div>
<div class="overflow-visible">Visible overflow</div>
<div class="overflow-scroll">Scroll overflow</div>

<!-- Cursor -->
<div class="cursor-pointer">Pointer cursor</div>
<div class="cursor-default">Default cursor</div>
<div class="cursor-not-allowed">Not allowed cursor</div>
```

## 📱 Responsive Design

### Breakpoints
- **XS**: 0px - 575px (Mobile)
- **SM**: 576px - 767px (Large Mobile)
- **MD**: 768px - 991px (Tablet)
- **LG**: 992px - 1199px (Desktop)
- **XL**: 1200px - 1399px (Large Desktop)
- **XXL**: 1400px+ (Extra Large Desktop)

### Responsive Utilities
```html
<!-- Responsive Visibility -->
<div class="d-none d-md-block">Visible on tablet+</div>
<div class="d-block d-lg-none">Hidden on desktop+</div>

<!-- Responsive Spacing -->
<div class="p-2 p-md-4 p-lg-6">Responsive padding</div>

<!-- Responsive Grid -->
<div class="col-12 col-sm-6 col-md-4 col-lg-3">Responsive columns</div>
```

## 🎨 Common Patterns

### Navigation Bar
```html
<nav class="bg-white border-bottom">
    <div class="container">
        <div class="d-flex justify-content-between align-items-center py-3">
            <h1 class="h3 mb-0">Logo</h1>
            <div class="d-flex gap-4">
                <a href="#" class="text-decoration-none text-dark">Home</a>
                <a href="#" class="text-decoration-none text-dark">About</a>
                <a href="#" class="text-decoration-none text-dark">Contact</a>
            </div>
        </div>
    </div>
</nav>
```

### Hero Section
```html
<section class="py-8 bg-primary text-white">
    <div class="container text-center">
        <h1 class="h1 mb-4">Welcome to My Site</h1>
        <p class="text-xl mb-6">A beautiful hero section built with GlacierCSS</p>
        <button class="btn btn-light btn-lg">Get Started</button>
    </div>
</section>
```

### Card Grid
```html
<div class="container">
    <div class="row">
        <div class="col-12 col-md-6 col-lg-4 mb-4">
            <div class="card">
                <div class="card-body">
                    <h4 class="card-title">Card 1</h4>
                    <p class="card-text">Card content here.</p>
                </div>
            </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 mb-4">
            <div class="card">
                <div class="card-body">
                    <h4 class="card-title">Card 2</h4>
                    <p class="card-text">Card content here.</p>
                </div>
            </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4 mb-4">
            <div class="card">
                <div class="card-body">
                    <h4 class="card-title">Card 3</h4>
                    <p class="card-text">Card content here.</p>
                </div>
            </div>
        </div>
    </div>
</div>
```

### Form Layout
```html
<div class="container">
    <div class="row justify-content-center">
        <div class="col-12 col-md-8 col-lg-6">
            <div class="card">
                <div class="card-body">
                    <h4 class="card-title text-center mb-4">Contact Form</h4>
                    <form>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Your Name">
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Your Email">
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="5" placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</div>
```

## 📚 Need More?

- **Full Documentation**: Check the main README.md
- **Examples**: View the examples/ folder
- **Source Code**: Explore the src/ folder for customization
- **GitHub**: https://github.com/jerankda/GlacierCSS

---

**Happy coding with GlacierCSS!** 🎨✨
