# Djurgalleriet

This project is a simple static landing page that displays a gallery of large animals. The page is built with plain HTML and CSS and can be served locally through an npm script without any frontend framework.

## Contents

- `index.html` contains the page structure and the animal cards.
- `styles.css` contains the layout, colors, and typography.
- `ANIMALS.md` is the source text with the list of animals.
- `package.json` contains the script for the local server.

## Run Locally

Requires `npm` and `python3`.

```bash
npm run serve
```

This starts a simple static server at:

```text
http://localhost:3000
```

## About The Site

The page works as an initial landing page with:

- a clear hero section
- a responsive gallery with animal images
- external image loading via Wikimedia Commons

Because it is a static site, it is easy to extend later with more pages, local image handling, or JavaScript if needed.
