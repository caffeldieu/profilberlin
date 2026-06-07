# Profil Vermögensmanagement GmbH – Website

Static website for [profilberlin.de](https://www.profilberlin.de).

## Structure

```
index.html        – Main landing page
impressum.html    – Impressum (legal disclosure)
datenschutz.html  – Datenschutzerklärung (privacy policy)
agb.html          – Allgemeine Geschäftsbedingungen (terms)
styles.css        – Shared custom styles
logo.png          – Company logo
favicon.png       – Favicon (32x32)
vercel.json       – Vercel deployment config
```

## Tech stack

- Plain HTML + CSS
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Montserrat](https://fonts.google.com/specimen/Montserrat) via Google Fonts
- [Formspree](https://formspree.io/) for contact form submissions
- Hosted on [Vercel](https://vercel.com/)

## Local development

Open `index.html` in a browser. No build step required.

For a local server (optional):

```bash
npx serve .
```

## Deployment

Push to the linked Vercel project. Vercel auto-detects static files and deploys with clean URLs (`/impressum` instead of `/impressum.html`).
