# GlacierCSS

A high-performance, minimalistic CSS framework designed for speed and beauty with excellent mobile support.

## 🚀 Features

- **Performance First**: Optimized for speed with minimal CSS output
- **Mobile-First**: Responsive design built from the ground up
- **Minimalistic**: Clean, semantic classes that don't bloat your HTML
- **Modern**: Built with modern CSS features and best practices
- **Lightweight**: Under 10KB gzipped for the core framework
- **Flexible**: Easy to customize and extend

## 📱 Mobile Support

- Mobile-first responsive grid system
- Touch-friendly button sizes and spacing
- Optimized typography for mobile screens
- Flexible breakpoints for all device sizes

## 🎨 Design Philosophy

GlacierCSS follows the principle of "less is more" - providing essential styling without overwhelming your design. The framework focuses on:

- Clean, readable typography
- Consistent spacing and sizing
- Subtle shadows and borders
- Accessible color contrasts
- Smooth animations and transitions

## 🚀 Quick Start

### Installation

**NPM (Recommended):**
```bash
npm install glaciercss
```

**CDN:**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glaciercss@1.0.0/dist/glaciercss.min.css">
```

**Direct Download:**
Download the latest release from GitHub and include `glaciercss.min.css` in your project.

### Basic Usage

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
        <h1 class="h1">Hello GlacierCSS!</h1>
        <div class="row">
            <div class="col-12 col-md-6">
                <div class="card">
                    <div class="card-body">
                        <h4 class="card-title">Responsive Card</h4>
                        <p class="card-text">This card automatically adapts to screen size!</p>
                        <button class="btn btn-primary">Get Started</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
```

## 📚 Examples & Templates

### (soon Live) Demo
- **[Complete Demo](examples/demo.html)** - Comprehensive showcase of all features
- **[Shop Template](examples/shop-template.html)** - E-commerce website template
- **[Portfolio Template](examples/portfolio-template.html)** - Professional portfolio template

### Template Features

**🛍️ Shop Template:**
- Responsive product grid
- Category navigation
- Shopping cart functionality
- Newsletter signup
- Mobile-first design

**🎨 Portfolio Template:**
- Hero section with skills
- Project showcase
- Work experience timeline
- Contact form
- Social media integration

All templates are fully responsive and demonstrate GlacierCSS's capabilities for real-world projects.

## 🛠️ Development

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/glaciercss.git
cd glaciercss

# Install dependencies
npm install

# Build the framework
npm run build

# Watch for changes during development
npm run dev
```

### Build Commands

- `npm run build` - Build the framework (expanded)
- `npm run build:min` - Build minified version
- `npm run watch` - Watch for changes and rebuild
- `npm run dev` - Build and start watching

## 📁 Project Structure

```
glaciercss/
├── src/
│   ├── base/           # Base styles (reset, typography, etc.)
│   ├── components/     # Component styles
│   ├── layout/         # Layout utilities (grid, containers)
│   ├── utilities/      # Utility classes
│   ├── variables/      # SCSS variables and mixins
│   └── main.scss       # Main entry point
├── dist/               # Compiled CSS files
├── examples/           # Example HTML files
└── docs/              # Documentation
```

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE11+ (with polyfills)

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome!

- Create an issue for bugs or feature requests
- Check the documentation for common questions

---

Built with ❤️ for the modern web.
