# consent-driven-development
stupid hackathon 2025 (67)
# Weldon Seat Sonar (Browser Edition)

Detect chairs & people locally in your browser (COCO-SSD). Plays a sonar ping when an empty chair is seen.

## Quick start
1) Download and unzip this folder.
2) Open a terminal in the folder and run a tiny local server:
   - Python 3: `python3 -m http.server 8000`
   - or Node:  `npx serve`
3) Visit http://localhost:8000 in your browser.
4) Click **Start Camera**. Choose your camera. Adjust confidence & cooldown.
5) (Optional) Upload a custom sound in the controls. A default `assets/sonar.mp3` is included.
6) Snapshot saves a PNG with overlays.

Everything runs on-device; no video is uploaded anywhere.
