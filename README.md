# Airport Live v0.1 ✈️

A responsive, dark aviation dashboard for discovering airport camera feeds.

## Included in v0.1

- Featured LAX YouTube embed: `n4I0d44oBEs`
- Searchable airport cards for LAX, JFK, SFO, LHR, SIN, and HND
- Responsive layout for desktop, tablet, and mobile
- Illustrative world-map panel and camera availability notes
- No framework or build step required — the app is a single static `index.html`

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/(root)`, then save.
4. Wait for GitHub Pages to publish the site.

## Important note about the stream

The LAX video is embedded from YouTube using its official embed player. If a network blocks YouTube domains, the embedded player may also be blocked. This app does not proxy or bypass network restrictions. Other camera providers can be added after their feeds and embedding permissions are verified.

## Roadmap

- [ ] Add verified non-YouTube camera sources
- [ ] Make airport markers interactive
- [ ] Save favorite airports
- [ ] Add camera status and airport local times
- [ ] Replace the illustrative map with a real interactive map
