# Poligono Website

Static GitHub Pages site for Poligono, a visual technology and architectural visualisation studio working across architectural imagery, digital twins, OpenUSD workflows, real-time environments, and technical 3D pipeline development.

The site uses semantic HTML, responsive CSS, and minimal vanilla JavaScript only. There is no build system, package manager, framework, or external JavaScript dependency.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Static assets only
- GitHub Pages hosting

## Local Preview

You can preview the site in either of these ways:

- Open `index.html` directly in a browser.
- Use the VS Code Live Server extension and serve the repository root.

## Folder Structure

```text
poligono-site/
|-- index.html
|-- README.md
|-- CNAME
|-- assets/
|   |-- brand/
|   |   `-- poligono-sphere.svg
|   |-- images/
|   |   `-- .gitkeep
|   |-- video/
|   |   `-- .gitkeep
|   `-- icons/
|       `-- .gitkeep
|-- css/
|   `-- styles.css
`-- js/
    `-- main.js
```

## GitHub Pages Deployment

This project is ready to deploy from GitHub Pages without a build step.

Recommended settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`

The site is intended to work from:

```text
https://poliport.github.io/poligono-site/
```

The `CNAME` file is intentionally empty for now. Add the final custom domain only when the domain is ready to connect through VentraIP DNS.

## Brand Notes

- The primary brand mark is a live-text `POLIGON` wordmark with a reusable SVG sphere replacing the final `O`.
- The sphere asset lives at `assets/brand/poligono-sphere.svg`.
- The hero descriptor line is `VISUALISATION / DIGITAL TWINS / OPENUSD`.
- Generated concept imagery is reference only and should not be used as a production logo or website asset.

## Future Improvements

- Add real project imagery.
- Add case study pages.
- Add technical workflow pages if needed later.
- Optimise image loading.
- Connect the custom domain through VentraIP when ready.
