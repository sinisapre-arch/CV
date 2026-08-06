# Sinisa Predragovic — CV / Portfolio Website

Personal CV website for Sinisa Predragovic (Синиша Предрагович) — Landscape Designer, 3D Visualizer & AI Artist.

## Features
- Single-page, print-friendly CV site
- Bilingual RU / EN toggle (remembers choice via localStorage)
- Dark forest + gold theme with noise overlay and scroll progress bar
- Reveal-on-scroll animations (CSS fallback, respects `prefers-reduced-motion`)
- Responsive layout + print styles (use browser Print → Save as PDF)
- No build step — pure HTML/CSS/JS, hosted on GitHub Pages

## Structure
- `index.html` — the entire site
- `assets/profile.jpg` — profile photo
- `extract-photo.py` — one-off script to pull the photo from the source cover letter

## Local preview
```bash
python -m http.server 8080
# open http://localhost:8080
```

## Deploy
Hosted via GitHub Pages (branch: `main`, root). Push to `main` to publish.
