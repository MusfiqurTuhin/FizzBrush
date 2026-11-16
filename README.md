# FizzBrush

A static multi-page website for "FizzBrush", a painting and decorating business. Headlines on the pages read "Elevating Spaces with Expert Precision" and "Explore Our Painting and Decorating Solutions".

## What it does

Five HTML pages share one layout and navigation: `index.html` (home), `about.html`, `service.html`, `feature.html` and `contact.html`. Behaviour such as the carousel and scroll animations lives in `js/main.js`.

## Tech stack

- HTML, CSS and JavaScript
- Bootstrap 5, with the Bootstrap SCSS sources in `scss/` and the primary colour, fonts and body colour customised in `scss/bootstrap.scss`
- jQuery, Bootstrap Icons and Google Fonts (Open Sans, Playfair Display), loaded from CDNs
- Bundled libraries in `lib/`: Animate.css, easing, Owl Carousel, Waypoints and WOW.js

## Folder layout

```
*.html        the five pages
css/          compiled Bootstrap and site styles
scss/         Bootstrap SCSS source and customisation
js/main.js    site scripts
lib/          third-party front-end libraries
img/          images and web manifest
```

## Run

There is no build step or package manifest in the repository. Open `index.html` in a browser, or serve the folder with any static file server. An internet connection is needed for the CDN assets. Recompiling `scss/bootstrap.scss` to `css/bootstrap.min.css` needs an SCSS compiler, which is not configured here.

## Environment variables

None.

## Status

A static site with no tests and no backend.
