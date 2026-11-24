# Etran Landing Page

Responsive landing page (mobile / tablet / desktop) written with HTML and SCSS.
Design: Figma. Fonts: Manrope, IBM Plex Sans.

## Run

```bash
npm install
npm run build   # compile SCSS once
npm run sass    # compile and watch while working
```

Then open `index.html` in the browser.

## Structure

- `scss/abstracts` variables and mixins
- `scss/base` reset and typography
- `scss/components` logo, button, offerings, quick links, sponsors, cards
- `scss/layout` header, main, footer
- `assets/img` all images (renamed: `icon-*`, `brand-*`, `stat-*`, `hero-*`)
- `assets/css/main.css` compiled output
