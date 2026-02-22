# Focal Landing Page

## Run locally
1. Open `index.html` directly in your browser.
2. Or serve the folder with a simple static server (optional), for example:
   - `python -m http.server 8000`
   - Then open `http://localhost:8000`

## Customize
- Brand/content text: edit semantic sections in `index.html` (`hero`, `problem`, `how it works`, `why now`, `waitlist`, `footer`).
- Colors and spacing: update CSS variables under `:root` in `index.html`.
- Signal animation intensity: tune `@keyframes scan`/`pulse` and related opacities.
- Waitlist storage key: change `focal_waitlist_email` in the inline script.