# Appointment Booking

A self-contained, single-page appointment booking app (HTML, CSS and JavaScript in one file).

## Run it
Open `index.html` in any modern browser. No build step or server is required.

Optional local server:

    python3 -m http.server 8000
    # then visit http://localhost:8000

## Notes
- Data is saved in the browser's `localStorage` (per browser, per device).
- QR codes use the `qrcode-generator` library loaded from cdnjs, so an internet connection is needed for that feature.
- Supports light and dark themes automatically.

## Deploy
Upload `index.html` to any static host (GitHub Pages, Netlify, Vercel, etc.).
