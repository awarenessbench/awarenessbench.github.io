# awarenessbench.github.io

Source for [awarenessbench.github.io](https://awarenessbench.github.io) — currently a Coming Soon placeholder. The full paper landing page will be published here after the paper goes public.

## Structure

```
awarenessbench.github.io/
├── index.html                — Coming Soon page
├── .nojekyll                 — tells GitHub Pages to serve as plain static files
└── static/
    └── css/style.css         — minimal styling (light + dark mode)
```

No build step. Edit `index.html` → push → live in ~30 seconds.

## Local preview

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Switching to the full paper page later

When the paper is ready, replace `index.html` with the full landing layout (hero / authors / abstract / BibTeX / etc.). An earlier version of that template is in git history — `git log --all` to find it, or clone the initial commit.
