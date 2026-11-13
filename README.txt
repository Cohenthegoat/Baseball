PITCHLAB PWA prototype

Files:
- index.html: app interface
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icon-192.png and icon-512.png: app icons

To install on iPhone:
1. Host this folder on an HTTPS static host (for example, a static site deployment).
2. Open the deployed URL in Safari.
3. Tap Share > Add to Home Screen.
4. Enable Open as Web App if shown, then tap Add.

Important:
- A PWA must be served from HTTPS or localhost for service workers and installability.
- This prototype stores data in browser localStorage on one device. It has no accounts or cloud sync.
- The assistant is rule-based demo logic, not a connected AI model.
- The app does not provide medical advice or clear athletes to throw.
