# PMI Austin Site Clone

This repository contains a static clone of https://pmiaustin.org front page.

## Usage
- The static file is in `index.html`.
- `.nojekyll` is present to avoid Jekyll processing.
- Deployment is automated by GitHub Actions in `.github/workflows/pages-deploy.yml`.

## Deployment URL
- `https://pmiaustin.github.io/pmiaustin-site/` (after GitHub Pages is active)

## Status checks (local)
- `python3 -m http.server 8000`
- open `http://localhost:8000` to preview locally.

