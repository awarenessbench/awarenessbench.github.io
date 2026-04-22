# awarenessbench.github.io

Source for [awarenessbench.github.io](https://awarenessbench.github.io) — a placeholder landing page for an upcoming research paper.

## Structure

```
awarenessbench.github.io/
├── index.html                — page markup + placeholder content
├── .nojekyll                 — tells GitHub Pages to serve as plain static files
└── static/
    ├── css/style.css         — all styling (light + dark mode)
    └── images/               — drop your teaser / result figures here
```

No build step. Open `index.html` in a browser and you're editing the live version.

## What to replace

In `index.html`, look for these placeholder spots:

| Location | What to replace |
|:--|:--|
| `<title>`, `<meta name="description">`, `og:*` | Paper title + one-line description |
| `.venue` | Venue + year (e.g. `NeurIPS 2026`) |
| `.title` | Paper title + optional subtitle |
| `.authors` | Author names, link each to their homepage |
| `.affiliations` | Institution names keyed to author `<sup>` numbers |
| `.links` | `href` on each button — Paper / arXiv / Code / Data / BibTeX |
| `.teaser` | Swap the `placehold.co` URL for your figure in `static/images/` |
| `Abstract` section | Real abstract (150–250 words) |
| `Headline Result` section | Delete or fill with real figure |
| `#bibtex` | Real BibTeX entry |
| Footer | Contact email + GitHub repo link |

## Local preview

```bash
# Python 3
python -m http.server 8000
# or Node
npx serve .
```

Then open http://localhost:8000.

## Deployment

GitHub Pages at `awarenessbench.github.io` auto-deploys from the default branch (`main`). Push to `main` → live in ~30 seconds.
