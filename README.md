# Asad CBSE Tracker — PWA

This version adds Progressive Web App support while keeping the existing tracker UI and functionality.

## GitHub Pages deployment

1. Upload `index.html`, `manifest.json`, `sw.js`, and the `icons` folder to the same repository/folder.
2. Make sure the main page is named exactly `index.html`.
3. In GitHub: **Settings → Pages**.
4. Select **Deploy from a branch**, choose your branch (usually `main`) and `/root`.
5. Open the generated GitHub Pages HTTPS URL.
6. On supported browsers, use **Install app / Add to Home screen**.

## Included PWA features

- Installable app experience
- Standalone display mode
- Offline app-shell caching
- Automatic service-worker update handling
- 192×192 and 512×512 app icons
- Android/Chrome and iOS PWA metadata
