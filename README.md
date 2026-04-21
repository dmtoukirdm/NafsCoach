# Toukir's Flow — Muslim Daily Tracker

This project was converted from a single-file HTML app into a cleaner multi-file static app structure.

## Structure
- `index.html` — main app shell
- `assets/css/` — extracted CSS files
- `assets/js/` — extracted JavaScript files
- `assets/icons/` — extracted icon assets
- `manifest.webmanifest` — PWA manifest
- `sw.js` — service worker fallback
- `package.json` — simple local serve script

## Run locally
```bash
python -m http.server 4173
```
Then open `http://localhost:4173`

## Notes
- The original app logic and styling were preserved as much as possible.
- External dependencies already used by the original HTML were left intact.
