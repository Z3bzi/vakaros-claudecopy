# vakaros-claudecopy

**Startline** — a single-page sailing start-timer and start-line app for phones.

## Features

- Countdown timer with sync-to-nearest-minute, ISAF-style sound signals and optional rolling restart
- Ping the pin and RC ends to compute line length, bearing, square-line wind and end bias
- Live distance to line, time-to-burn, OCS warning, SOG/COG/heading, heel and VMG
- After the gun the countdown clears away and heading, COG and speed take over the screen
- Rolling heading average (20/30/40 s) calls lifts and headers for the tack you are on,
  with a green or red light blinking in the top corner the wind has shifted to
- Tack and gybe detection: the shift baseline restarts on each one, and tacks are counted
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
