# Masrur Sabab Khan Chowdhury — Portfolio

Personal portfolio website hosted on GitHub Pages.

**Live site:** https://masrursababkhanchowdhury.info.bd/

## Overview

This repository contains the production-ready static build of the portfolio.
The app itself is bundled JavaScript/CSS under `assets/`, and `index.html` boots the application.

## Tech Snapshot

- Static hosting: GitHub Pages
- Frontend runtime: React (bundled output)
- Entry point: `index.html`
- Assets: `assets/index-ByZU6W7G.js`, `assets/index-C2MNsA8d.css`

## Project Structure

```
.
├─ CNAME
├─ index.html
├─ 404.html
├─ robots.txt
├─ sitemap.xml
├─ site.webmanifest
├─ .nojekyll
└─ assets/
   ├─ index-ByZU6W7G.js
   └─ index-C2MNsA8d.css
```

## Local Preview

Because this is a static output, use any lightweight local server:

### Python

```bash
python -m http.server 8080
```

Then open: `http://localhost:8080`

### VS Code Live Server

Open the folder and run **Live Server** on `index.html`.

## Deployment

This repository is configured for GitHub Pages custom domain deployment:

- `CNAME` points to `masrursababkhanchowdhury.info.bd`
- `.nojekyll` ensures static assets are served without Jekyll processing
- `404.html` supports SPA-style route fallback

## Maintenance Notes

- `index.html` holds SEO/social metadata and app bootstrap tags.
- If you rebuild the frontend from source, replace files in `assets/` and update references in `index.html` if filenames change.
- Keep `sitemap.xml` and `robots.txt` aligned with canonical domain.

## License

All rights reserved unless stated otherwise.