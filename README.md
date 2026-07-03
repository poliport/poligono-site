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
|   |   `-- projects/
|   |       |-- aami-park.jpg
|   |       |-- adelaide-oval.jpg
|   |       |-- barangaroo-concept.jpg
|   |       |-- branz-yonban-cho.jpg
|   |       |-- broderick-rd-industrial-facility.jpg
|   |       |-- como-the-arch.jpg
|   |       |-- custodian-project.jpg
|   |       |-- healthcare-housing-development.jpg
|   |       |-- heathrow-t5.jpg
|   |       |-- lloyds-corner.jpg
|   |       |-- melbourne-convention-centre.jpg
|   |       |-- mlmc-cafeteria-staff-office.jpg
|   |       |-- mlmc-redevelopment.jpg
|   |       |-- obic-midosuji.jpg
|   |       |-- shorts-place.jpg
|   |       |-- syscon-vr.jpg
|   |       `-- triangle-house.jpg
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

## Migrated Image Assets

Project images migrated from the existing Wix site are stored locally in `assets/images/projects/` and referenced from `index.html` as repository assets. Wix-hosted image URLs were used only as source references during migration and should not be used directly in production HTML or CSS.

The migrated project covers were optimised to JPG files with ImageMagick so the static site remains lightweight and still works by opening `index.html` directly.

The requested `IMG_1893_edited.jpg` profile image was not exposed in the inspected Wix homepage or About page payloads, so no profile image was added to the current About section. If the source file becomes available, place it under `assets/images/profile/` and reference it locally.

## Temporary Font Testing

The `<body>` element has a temporary font testing class. Switch typography directions by changing that single class:

- `theme-font-a-space-inter`: Space Grotesk for display, logo, hero, and headings; Inter for body and UI.
- `theme-font-b-sora-inter`: Sora for display, logo, hero, and headings; Inter for body and UI.
- `theme-font-c-plex`: IBM Plex Sans for display, headings, body, and UI; IBM Plex Mono for technical labels only.
- `theme-font-d-cal-inter`: Cal Sans for display, logo, hero, and headings; Inter for body and UI.

Remove this testing system once the final font direction is selected.

## Future Improvements

- Add case study pages.
- Add technical workflow pages if needed later.
- Optimise image loading.
- Connect the custom domain through VentraIP when ready.
