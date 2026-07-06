# TAXI — Такси Бургас / Burgas Taxi website

Responsive marketing / portfolio website for a taxi & airport-transfer company in Burgas, Bulgaria.

## Contents
- `index.html` — Bulgarian version (default / priority)
- `index-en.html` — English version

The two pages are linked via the BG/EN switcher in the header.

## Features
- Fully responsive — fluid `clamp()` typography and auto-reflowing grids from ~320px phones to 4K/ultra-wide screens
- Sections: hero, fleet, fixed-price table, services, online booking form, why-us, FAQ, testimonials, footer
- Self-contained (single file each — inline CSS/JS), no build step

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
Push to GitHub, then in the repo: **Settings → Pages → Build from branch → `main` / root**.
The Bulgarian page will be served at the repo's Pages URL by default.

## To do
- Replace placeholder car photos, phone numbers and email
- Connect the booking form to an email address or booking system
