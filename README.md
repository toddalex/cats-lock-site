# catslock.app

Marketing and legal pages for [Cats Lock](https://catslock.app) — a macOS app for cat people.

Hosted on GitHub Pages. Plain HTML + CSS, no build step.

## Structure

```
├── index.html          Landing page
├── privacy.html        Privacy policy
├── CNAME               Custom domain binding (catslock.app)
└── assets/
    ├── logo/           Brand mark
    └── screenshots/    App screenshots (downscaled from 2880×1800 for web)
```

## Local preview

Open `index.html` directly in a browser, or serve from the repo root:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Deployment

Pushes to `main` publish automatically via GitHub Pages.

## License

MIT — see [LICENSE](LICENSE).
