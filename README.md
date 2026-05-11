# Amazon Clone

A pixel-perfect front-end clone of Amazon's homepage built with HTML and CSS, using real images sourced directly from Amazon's CDN.

## Features

- Sticky navbar with search bar, category dropdown, cart counter, and account links
- Auto-sliding hero carousel (4 real Amazon banners, 5s interval) with prev/next controls
- Product category cards in a responsive 4-column grid
- Special category card layout (main image + sub-category thumbnails)
- Best Sellers sections with real Amazon product images
- "Sign in for best experience" card
- Complete footer — 4-column links, language/currency selectors, 25 Amazon subsidiary brands
- India redirect banner

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox)
- Vanilla JavaScript (carousel logic)
- Font Awesome 6 (icons)

## Structure

```
Amazon-Clone/
├── index.html       # Main page
├── Amazon.css       # All styles
├── amazonlogo.png   # Amazon logo
└── usa.jpg          # US flag (language selector)
```

## Run Locally

Open `index.html` in any browser — no build step or server needed.

> Images load from Amazon's CDN so an internet connection is required for product images.
