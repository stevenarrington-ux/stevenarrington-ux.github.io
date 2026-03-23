# Steve Arrington — Portfolio

A modern portfolio site for Principal/Director-level product design roles. Built with vanilla HTML, CSS, and JavaScript.

## Features
- **Dark theme by default** with light/dark mode toggle (persists via localStorage)
- **Per-project accent colors** — each case study has a distinct header color reflected in homepage thumbnails
- **Scannable case studies** — consistent section headings (Summary, The Challenge, How I Led This, etc.)
- **Responsive** — mobile-friendly layout
- **Assets** — all images from steve-arrington.super.site

## Pages
- `index.html` — Homepage with hero, case studies, design systems, testimonials, mentoring, contact
- `about.html` — About Me
- `brivo.html` — Brivo Security Suite case study
- `carina.html` — Carina Design System case study
- `ai-enhancements.html` — AI Enhancements case study
- `building-design-led.html` — Building a Design-Led Organization
- `ai-experiments.html` — AI experiments and design games

## Run locally
Open `index.html` in a browser, or use a simple local server:

```bash
# Python 3
python -m http.server 8000

# Node (npx)
npx serve .
```

Then visit http://localhost:8000

## Deploy
Upload the folder contents to any static hosting (Netlify, Vercel, GitHub Pages, etc.). No build step required.
