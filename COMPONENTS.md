# ArcadeNeon — Components

Single-file static web app: a neon-themed retro arcade landing/game page.
**No build system, no services, no external libraries.**

## systemd services

None.

## Libraries / dependencies

None. Fully self-contained: no CDN scripts, no external stylesheets, no fonts
fetched over the network.

## Contents

| File | Description |
|---|---|
| `index.html` | The entire app — HTML + inline CSS + inline JavaScript (~86 KB) |
| `preview.png` | Screenshot preview of the UI |
| `screenshots/` | Additional screenshots |

## Notes

- Runs by opening `index.html` in any browser (or serving the directory with any static file server).
- No server-side state; everything is client-side.
