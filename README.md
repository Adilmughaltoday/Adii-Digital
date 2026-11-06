# Adii Digital

A responsive one-page website for **Adii Digital**, a founder-led digital marketing agency that helps small and growing businesses get found, get leads, and grow through SEO, Google & Meta Ads, social media, content, and email marketing.

**Live agency website:** [adiidigital.com](https://adiidigital.com)

## About this project

This repository contains a lightweight static website built with plain HTML, CSS, and vanilla JavaScript — no frameworks and no build step. It presents the agency, its services, and how to get in touch.

The site's own sections:

- **Hero** — "Make your next move count."
- **Services** — Strategy, Brand & Creative, Digital Growth, and Content & Social
- **Work** — illustrative project concepts (as labelled on the page itself)
- **About** — how the agency works with clients
- **Contact** — a call to action to start a conversation

## Tech stack

- HTML5
- CSS3 (single `styles.css`, responsive layout)
- Vanilla JavaScript (single `script.js` — mobile navigation toggle and footer year)
- Google Fonts: Manrope and DM Sans

## Project structure

```
.
├── index.html   # Page markup and content
├── styles.css   # All styling
├── script.js    # Mobile menu + footer year
└── README.md
```

## Run it locally

No build tools are needed. Either:

1. Open `index.html` directly in a browser, or
2. Serve the folder with any static server, for example:

   ```bash
   npx serve .
   # or
   python3 -m http.server 8000
   ```

   Then open http://localhost:8000 (or the port your server shows).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to propose changes. In short: branch from `main`, keep changes focused, and open a pull request — please don't push directly to `main`.

## Contact

- Website: https://adiidigital.com
- Email: contact@adiidigital.com
- Free digital marketing audit: https://adiidigital.com/digital-marketing-audit/

---

© Adii Digital. All rights reserved. This repository is the agency's own website code; it is not licensed for reuse — see the repository owner for permission.
