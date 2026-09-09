# eitanrapa.github.io

Personal academic website for Eitan Rapaport Bruck, served by GitHub Pages.

Static HTML and CSS — no build step. Push to `main` and GitHub Pages publishes it.

## Structure

```
index.html              Home — about, contact, academic experience
research/index.html     Research
publications/index.html Publications
assets/css/style.css    All styling
assets/img/             Images
assets/cv/              CV (PDF)
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Notes

Typography and color follow the previous site: Cormorant SC for display type,
DM Sans for body text, `#111111` on white, 920px content column. Fonts load from
Google Fonts.

To update the CV, replace `assets/cv/Eitan_Rapaport_Bruck_CV.pdf` (the filename
is referenced from `index.html`).
