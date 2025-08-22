# GlacierCSS Quick Start Guide

Get up and running with GlacierCSS in minutes!

## 🚀 Installation

### Option 1: NPM (Recommended)
```bash
npm install glaciercss
```

### Option 2: Download
Download the latest release from GitHub and include the CSS file in your HTML.

## 📝 Basic Setup

Add this to your HTML `<head>` section:

```html
<link rel="stylesheet" href="glaciercss.min.css">
```

## 🎯 Your First Page

Here's a minimal example to get you started:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GlacierCSS Page</title>
    <link rel="stylesheet" href="glaciercss.min.css">
</head>
<body>
    <div class="container">
        <h1 class="h1">Hello, GlacierCSS!</h1>
        <p class="text">This is a beautiful, fast page built with GlacierCSS.</p>
        <button class="btn btn-primary">Get Started</button>
    </div>
</body>
</html>
```

## 🏗️ Grid System

GlacierCSS uses a mobile-first 12-column grid system:

```html
<div class="container">
    <div class="row">
        <div class="col-12 col-md-6 col-lg-4">
            <div class="card">Content</div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
            <div class="card">Content</div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
            <div class="card">Content</div>
        </div>
    </div>
</div>
```

## 🎨 Components

### Buttons
```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-outline-primary">Outline</button>
<button class="btn btn-ghost-primary">Ghost</button>
```

### Cards
```html
<div class="card">
    <div class="card-header">
        <h4 class="card-title">Card Title</h4>
    </div>
    <div class="card-body">
        <p class="card-text">Card content goes here.</p>
    </div>
</div>
```

## 📱 Responsive Utilities

Use responsive prefixes for different screen sizes:

```html
<!-- Hidden on mobile, visible on medium screens and up -->
<div class="d-none d-md-block">Desktop Only</div>

<!-- Centered on mobile, left-aligned on large screens -->
<div class="text-center text-lg-left">Responsive Text</div>
```

## 🎯 Spacing Utilities

Quick spacing with utility classes:

```html
<div class="p-4">Padding on all sides</div>
<div class="m-2">Margin on all sides</div>
<div class="px-3">Horizontal padding</div>
<div class="py-5">Vertical padding</div>
```

## 🔧 Customization

### Using SCSS (Advanced)
If you want to customize the framework:

1. Clone the repository
2. Install dependencies: `npm install`
3. Modify variables in `src/variables/_variables.scss`
4. Build: `npm run build`

### Using CSS Custom Properties
Override CSS variables in your own CSS:

```css
:root {
    --primary: #your-color;
    --border-radius: 8px;
}
```

## 📱 Mobile-First Approach

GlacierCSS is built mobile-first. Start with mobile styles and use responsive prefixes to enhance for larger screens:

- `col-12` = Full width on all screens
- `col-md-6` = Half width on medium screens and up
- `col-lg-4` = One-third width on large screens and up

## 🎨 Design Principles

- **Minimal**: Clean, semantic classes
- **Fast**: Optimized CSS output
- **Accessible**: Built with accessibility in mind
- **Mobile**: Touch-friendly and responsive

## 🚀 Performance Tips

1. Use the minified version (`glaciercss.min.css`)
2. Only include the components you need
3. Leverage utility classes for common patterns
4. Use the grid system for consistent layouts

## 📚 Next Steps

- Check out the [full documentation](README.md)
- Explore the [example page](examples/index.html)
- Customize the framework to match your brand
- Build something amazing! 🎉

## 🤝 Need Help?

- Check the [README](README.md) for detailed documentation
- Look at the [examples](examples/) folder
- Open an issue on GitHub if you find a bug

---

**Happy coding with GlacierCSS!** 🎨✨
