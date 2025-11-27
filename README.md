# Coconut Thai Wellesley Website

Website for Coconut Thai Wellesley restaurant.

## Quick Start

This is a static HTML website. Simply open `index.html` in a browser or deploy to any static hosting service.

## File Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styles
├── script.js       # Mobile menu functionality
├── images/
│   ├── logo.png    # Restaurant logo
│   ├── hero.jpg    # Hero background image
│   └── favicon.ico # Browser favicon
└── README.md
```

## Editing Guide

### Update Hours
Edit the hours section in `index.html`:
```html
<section class="hours" id="hours">
```

### Update Contact Info
Edit the location section in `index.html`:
```html
<section class="location" id="location">
```

### Change Colors
Edit CSS variables at the top of `styles.css`:
```css
:root {
    --color-black: #000000;
    --color-white: #ffffff;
    ...
}
```

### Replace Images
Replace files in the `images/` folder with same filenames.

## Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select "main" branch as source
4. Site will be available at `https://coconutthai.github.io`

## Custom Domain

To use `www.coconut-thai-wellesley.com`:
1. Add a `CNAME` file with the domain name
2. Configure DNS at your domain registrar to point to GitHub Pages
