# AGENTS.md

Static single-file GitHub Pages site for Eduard Helmut (Freigericht beekeeper).

- Entire site is `index.html`: HTML + inline Tailwind + custom CSS/JS.
- Tailwind via CDN; theme extended inline (honey, wood, forest, cream, bark).
- Local images in `assets/` (6 JPGs). Use relative paths `assets/xxx.jpg`.
- No Node, package.json, build, lint, or tests. Edit HTML directly.
- All content must stay in German.
- Preview locally: `python3 -m http.server 8000` (or `npx serve`).
- Deploy: push to `main` (GitHub Pages serves root `index.html`).

Read this file before editing.