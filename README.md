# Terra & Cielo website

Static site (no build step): `index.html`, `journey.css`, `journey/`, `assets/`.

## Run locally
Double-click `index.html`, or serve the folder: `python -m http.server 8000` then open http://localhost:8000
(needs internet for Three.js and Google Fonts from CDNs).

## Publish on GitHub Pages
1. Create a repo and push all files in this folder (keep the folder structure).
2. Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://<user>.github.io/<repo>/`.

## Arrival journey
Plays on every visit. Add `?nojourney` to the URL to skip. See `journey/README.md`.
