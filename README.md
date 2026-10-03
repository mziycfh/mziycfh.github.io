# Yufan Zhang's academic website

A minimal static HTML + CSS website, adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io).

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. No build step or dependencies are required.

## Customize

- Edit `index.html` to update the bio, papers, contact links, and personal interests.
- Duplicate a `<li class="paper">` entry for each paper. Each entry contains only a title, authors, and venue/year.
- Replace the blank `.profile-photo` element with an image when ready, and adjust its styling in `stylesheet.css`.
- `stylesheet.css` preserves the original Lato font declarations, compact typography, and link colors. Lato is loaded from Google Fonts when available, with system font fallbacks.

GitHub Pages can serve these files directly.
