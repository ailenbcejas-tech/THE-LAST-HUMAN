# THE LAST HUMAN

A responsive browser game for the Nerdearla 2026 App Challenge: can you tell whether a piece of work was created by a human or an AI?

## Stack
Plain HTML, CSS and JavaScript. No external runtime, no API key, no build step.

## Run locally
Open `index.html` in a browser, or serve the folder with any static server.

## Webflow Cloud
The repository includes `webflow.json` configured as a `static` app. Webflow Cloud supports no-framework static apps and can deploy committed HTML/CSS/JS directly.

## Features
- 10 curated challenges across prose, chat, code and work documents
- Human / AI decision flow
- Immediate reveal and explanation
- Expandable signal analysis
- Score and responsive progress UI
- Human Fingerprint result screen
- Global Human Index placeholder designed for real persistent field data
- Responsive mobile layout
- Zero API keys required

## Next technical extension
Webflow Cloud supports SQLite/KV storage. A future server-side endpoint can record anonymized results and calculate the real Global Human Index without exposing secrets to the browser.
