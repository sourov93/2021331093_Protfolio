# Portfolio — Md. Shamshuddoha Sourov

Personal portfolio site. CSE, Shahjalal University of Science and Technology (2021331093).

Live: https://sourov93.github.io/2021331093_Protfolio/

## Structure

Plain static site — no build step, no dependencies to install.

- `index.html` — every section (About, Skills, Projects, Contact)
- `style.css` — custom styles on top of Tailwind
- `picme.jpg` — profile photo

Tailwind and Font Awesome load from a CDN, so an internet connection is needed to view it.

## Editing

Open `index.html` in a browser to preview locally. Push to `main` and
[the workflow](.github/workflows/deploy.yml) publishes it to GitHub Pages automatically.
