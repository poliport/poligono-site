# Poligono Website

Initial static website framework for Poligono, a premium 3D visualisation and architectural visualisation business.

The site is designed as a landing page and portfolio starter for GitHub Pages. It uses semantic HTML, responsive CSS, and minimal vanilla JavaScript only. There is no build system, package manager, framework, or external JavaScript dependency.

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
poligono-website/
├── index.html
├── README.md
├── CNAME
├── assets/
│   ├── images/
│   │   └── .gitkeep
│   ├── video/
│   │   └── .gitkeep
│   └── icons/
│       └── .gitkeep
├── css/
│   └── styles.css
└── js/
    └── main.js
```

## GitHub Pages Deployment

This project is ready to deploy from GitHub Pages without a build step.

Recommended settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`

For GitHub Free, the repository can be public to use GitHub Pages.

The `CNAME` file is intentionally empty for now. Add the final custom domain only when the domain is ready to connect through DNS.

## Future Improvements

- Add real project imagery.
- Add project case study pages.
- Optimise images for responsive delivery and performance.
- Configure custom domain DNS when the final domain is ready.
- Add analytics only if required later.
