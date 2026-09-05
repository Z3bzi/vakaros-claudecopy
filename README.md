# vakaros-claudecopy

**Startline** — a single-page sailing start-timer and start-line app for phones.

## Features

- Countdown timer with sync-to-nearest-minute, ISAF-style sound signals and optional rolling restart
- Ping the pin and RC ends to compute line length, bearing, square-line wind and end bias
- Live distance to line, time-to-burn, OCS warning, SOG/COG/heading, heel and VMG
- North-up line view with course-side shading and boat position
- GPX track recording and export, plus a demo mode with a simulated boat

## Running

The app is a single static file, `index.html` — open it directly in a browser,
or use the deployed GitHub Pages site.

GPS, compass and wake lock need a secure context (HTTPS or localhost), so use
the Pages URL on a phone rather than a local file.

## Deployment

Pushes to `main` are published by `.github/workflows/pages.yml`.
Enable it once under **Settings → Pages → Build and deployment → Source: GitHub Actions**.
