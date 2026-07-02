# berendmarkhorst.github.io

Personal academic website of Berend Markhorst, served with GitHub Pages at
[berendmarkhorst.github.io](https://berendmarkhorst.github.io).

A single static page — no build step, no framework.

- `index.html` — all content (about, news, publications, talks, teaching, CV)
- `style.css` — styling, with automatic dark mode via `prefers-color-scheme`
- `images/` — profile picture and favicon
- `.nojekyll` — tells GitHub Pages to serve the files as-is

To update the site, edit `index.html` and push to `master`.

Preview locally with:

```sh
python3 -m http.server
```
