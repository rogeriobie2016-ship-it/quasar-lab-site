# The Quasar Lab: spatial website prototype

Single-page site for The Quasar Lab, a research and design lab merging film, music, data, AR/VR and critical pedagogy. Built as one self-contained `index.html` (Three.js and GSAP from cdnjs, Google Fonts). No build step.

**Private study prototype, confidential, do not share.**

## Files

- `index.html`: the whole site
- `404.html`: not-found page
- `favicon.svg`, `site.webmanifest`: icon and app metadata
- `_headers`: Cloudflare Pages response headers (noindex, no framing); ignored by GitHub Pages
- `robots.txt`: blocks all crawlers
- `.nojekyll`: tells GitHub Pages to serve files as-is

## How deploys work

Live at https://rogeriobie2016-ship-it.github.io/quasar-lab-site/ via GitHub Pages (branch `main`, folder `/`). Pushing to `main` deploys; the site updates within a minute or two. The `noindex` meta tag keeps search engines from listing it, but anyone with the link can open it.

Paths are relative, so the same files also work on Cloudflare Pages if the site moves there later.

```bash
git add .
git commit -m "describe the change"
git push
```

## Local preview

```bash
npx serve .
```
