# Portfolio — Md. Shamshuddoha Sourov

Personal portfolio site. CSE, Shahjalal University of Science and Technology (2021331093).

Live: <https://sourov93.github.io/2021331093_Protfolio/>

## Structure

A single self-contained page — no build step, no dependencies to install.

- `index.html` — everything: markup, styles, scripts, and the profile photo
  (embedded as a base64 data URI, so there are no image files to keep in sync)

Google Fonts loads from a CDN, so an internet connection is needed for the
intended typography; the page still reads fine without it.

## Editing

Open `index.html` in a browser to preview locally. Push to `main` and
[the workflow](.github/workflows/deploy.yml) publishes it to GitHub Pages
automatically.

## History

Earlier versions live in the git history:

- The first portfolio (Tailwind CDN, separate `style.css` and `picme.jpg`) — commit `799ad8a`
- The unused Vite + React scaffold this repo started from — commit `44793a0`
