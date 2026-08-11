# Midsomar — devrel.midsomar.com

The Midsomar marketing site. A single static page — no build step, no framework.

## Structure

- `index.html` — the landing page (rendered HTML, self-contained)
- `assets/css/` — compiled stylesheet
- `assets/js/` — jQuery, `site.js`, and waypoints
- `assets/images/` — icons and landing graphics
- `assets/fonts/` — web fonts referenced by the stylesheet

## Deploy

Static site, served as-is by Vercel (see `vercel.json`). Nothing to build.

## Docs audit form

The form at the bottom posts to Formspree:

- Endpoint: `https://formspree.io/f/xwleopna`
- Submissions land in the Midsomar inbox.

To change the endpoint, edit `action` on `#audit-form` and the `$.ajax` call at the
bottom of `index.html`.