# alan-lanfeng.github.io

Personal website of [Lan Feng](https://alan-lanfeng.github.io/), PhD candidate at EPFL.

Built on the [Clarity Template](https://shikun.io/projects/clarity) by Shikun Liu. Deployed via GitHub Pages.

## Local preview

Just open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

- `index.html` — the landing page
- `clarity/` — Clarity template CSS/JS
- `assets/` — fonts, icons, figures, CV, stylesheets

## Deploy

Pushes to `main` auto-deploy to GitHub Pages via `.github/workflows/deploy.yml`.
