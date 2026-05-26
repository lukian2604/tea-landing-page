# TealuxE — Tea Landing Page

🔗 Live Site: [tealuxe](https://lukian2604.github.io/tea-landing-page/)

## About

TealuxE is a responsive landing page for a premium tea store. The design focuses on an elegant, minimal aesthetic with refined typography and a warm color palette — built entirely with HTML and CSS, no frameworks.

## Sections

- **Header** — navigation with logo, menu links and action icons (cart, account, search)
- **Hero** — full-bleed image section with tagline
- **Quote** — featured editorial quote
- **Explore our Collections** — tea type grid (Black, Green, White, Oolong, Pu-erh)
- **What our Clients say** — four-column review cards
- **Our Tea Blog** — two-column article card grid
- **Newsletter** — subscription form with privacy consent
- **We Prioritise** — four-column icon feature list
- **Footer** — product links, company links, contact info, social icons, payment methods

## Tech Stack

| Technology | Details |
|---|---|
| HTML5 | Semantic markup |
| CSS3 / SCSS | Custom properties, Flexbox, Grid |
| Fonts | Cormorant (Regular / Light / LightItalic), OpenSans (SemiBold / Light / LightItalic) — self-hosted `.woff2` |
| Icons | Inline SVG |
| Images | JPG / PNG / SVG assets |

## Project Structure

```
tea-landing-page/
├── index.html
├── fonts/                      # Self-hosted woff2 fonts
│   ├── Cormorant-Regular.woff2
│   ├── Cormorant-Light.woff2
│   ├── Cormorant-LightItalic.woff2
│   ├── OpenSans-SemiBold.woff2
│   ├── OpenSans-Light.woff2
│   └── OpenSans-LightItalic.woff2
├── images/
│   ├── blog/                   # 4 article images
│   ├── icons/                  # UI icons (SVG)
│   ├── payment-methods/        # Visa, Mastercard, PayPal, Google Pay
│   ├── prioritise/             # 4 feature icons (SVG)
│   ├── types-tea/              # 5 tea type images
│   ├── hero.jpg
│   └── logo.svg
└── styles/
    ├── styles.css              # Compiled CSS
    ├── styles.scss
    ├── _variables.scss
    ├── _fonts.scss
    ├── _globals.scss
    ├── _mixins.scss
    ├── _normalize.scss
    ├── _utils.scss
    ├── _media.scss
    └── blocks/                 # Per-component SCSS partials
```

## Getting Started

No build step required — open `index.html` directly in a browser or serve with any static file server:

```bash
# Using VS Code Live Server, or:
npx serve .
```

## Deployment

This project is deployed via GitHub Pages from the `main` branch root.
