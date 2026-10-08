# BAKO Tech

A modern single-page gaming & technology blog based on the supplied `indox.html`.

## Included
- `index.html` — main BAKO Tech blog
- `assets/bako-icon.svg` — original BAKO icon/favicon
- `manifest.webmanifest` — PWA metadata
- `sw.js` — service worker for basic offline caching
- `robots.txt` — crawler rules
- `sitemap.xml` — sitemap starter
- `.nojekyll` — GitHub Pages compatibility

## Run locally
Open `index.html` directly for the main UI. For PWA/service-worker features, use a local web server.

Example:
`python -m http.server 8080`

Then open:
`http://localhost:8080/`

## Before publishing
Replace `https://example.com/` in `index.html`, `robots.txt`, and `sitemap.xml` with your real domain.
Replace placeholder social/contact links with your real accounts.
