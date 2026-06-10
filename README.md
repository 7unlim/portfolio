# Junseo (Jun) Lim — Portfolio

A clean, dependency-free personal portfolio site. Plain HTML, CSS, and a little vanilla JavaScript — no build step, no frameworks.

## Structure

```
index.html    # Page content & structure
styles.css    # All styling (light + dark themes)
script.js     # Theme toggle, scroll reveal, footer year
```

## Run locally

It's a static site, so just open `index.html` — or serve it for a more accurate environment:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works. A few one-step options:

- **GitHub Pages** — push to a repo, enable Pages on the `main` branch (root).
- **Netlify / Vercel / Cloudflare Pages** — drag-and-drop the folder, or connect the repo. No build command needed; publish directory is the project root.

## Customize

- Content lives directly in `index.html`.
- Colors and type are defined as CSS variables at the top of `styles.css` (`:root` for light, `[data-theme="dark"]` for dark).
