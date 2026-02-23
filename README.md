# Personal Homepage + REFLEX Project Page

This repository is currently maintained as a static website (no Jekyll required for normal preview).

## Local preview

From the repository root, run:

```bash
python3 -m http.server 8000
```

Then open:

- `http://localhost:8000/` (homepage)
- `http://localhost:8000/reflex/` (REFLEX project page)

## Structure

- `index.html`: personal homepage
- `stylesheet.css`: homepage styles
- `reflex/index.html`: REFLEX project page (standalone static HTML)
- `assets/css/styles.css`: REFLEX page styles
- `assets/fig/`: REFLEX figure assets
- `img/`: homepage and publication thumbnails

## Notes

- Legacy Jekyll files (`_config.yml`, `_layouts/`) are kept for compatibility, but local preview does not depend on Jekyll.