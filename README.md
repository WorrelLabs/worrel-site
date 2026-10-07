<p align="center">
  <img src="logo.png" alt="Worrel: ensuring reliable work" width="360">
</p>

<p align="center">
  <strong>A trust layer for working life.</strong><br>
  Portable professional identity, built from evidence over time.
</p>

<p align="center">
  <a href="https://worrel.id">worrel.id</a>
</p>

---

## About Worrel

Worrel is an early-stage work identity and reliability platform, built first for the Turkish market. It aims to help people and organizations build trust through verifiable signals instead of self-reported claims.

This repository contains the public marketing site only. It does not contain the product, its data, or its source code.

## Product status

| Layer | Purpose | Status |
|---|---|---|
| Worrel ID | Portable professional identity | In development |
| WRS | Reliability signal built from evidence over time | In development |
| Pact | Visible expectations in working relationships | Planned |
| Signal | Patterns over time instead of single comments | Planned |
| Campus | Professional identity before graduation | Planned |
| Enterprise & Fly | Organizational context | Planned |

Products marked Planned or In development are not yet publicly available.

## About this repository

A single-page static site. There is no build step and no dependency to install.

```
.
├── index.html            Page markup and inline styles
├── 404.html              Not-found page
├── logo.png              Brand logo
├── favicon.png           Browser tab icon
├── apple-touch-icon.png  iOS home screen icon
├── og-image.png          Social sharing preview (1200×630)
├── robots.txt            Crawler rules
├── CNAME                 Custom domain for GitHub Pages
└── .nojekyll             Disables Jekyll processing
```

Fonts are loaded from Google Fonts at runtime.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

The site is served by GitHub Pages from the `main` branch (root folder) at [worrel.id](https://worrel.id). Pushing to `main` publishes the change.

## Contact

Visit [worrel.id](https://worrel.id).

## Copyright

© 2026 Worrel. All rights reserved. The Worrel name, logo and site content may not be reused without permission.
