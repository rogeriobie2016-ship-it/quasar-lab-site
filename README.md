# The Quasar Lab: spatial website prototype

Single-page site for The Quasar Lab, a research and design lab merging film, music, data, AR/VR and critical pedagogy. Built as one self-contained `index.html` (Three.js and GSAP from cdnjs, Google Fonts). No build step.

**Private study prototype, confidential, do not share.**

## Files

- `index.html`: the whole site
- `404.html`: not-found page
- `favicon.svg`, `site.webmanifest`: icon and app metadata
- `_headers`: Cloudflare Pages response headers (noindex, no framing)
- `robots.txt`: blocks all crawlers

## How deploys work

The repo is connected to Cloudflare Pages. Pushing to `main` deploys to production. Pushing any other branch creates a preview deployment. Both are protected by Cloudflare Access (email one-time PIN).

```bash
git add .
git commit -m "describe the change"
git push
```

## Local preview

```bash
npx serve .
```
