# hexagonsarebest.io — Starter

Minimal, elegant, humane Astro site. A+ C vibe: precise structure with soft warmth.

## Quickstart
```bash
# Node 18+ recommended
npm i
npm run dev
```

Build & preview:
```bash
npm run build
npm run preview
```

## Deploy
- **Vercel:** Import repo → Framework: Astro → Build: `npm run build` → Output: `dist`
- **Netlify:** New site from Git → Build command: `npm run build` → Publish directory: `dist`
- **GitHub Pages:** `npm run build` then publish `/dist`

## Structure
- `src/layouts/Base.astro` shared layout + typography
- `src/pages/` route files
  - `/` homepage (philosophy)
  - `/garden` living notes index
  - `/projects` experiments index
  - `/about` values-forward profile
- `public/` static assets

## Customise
- Edit colours in `src/styles/global.css`
- Replace `public/favicon.svg`
- Write new notes in `src/pages/garden/*.md`
- Add projects under `src/pages/projects/*.md`

---
_“architecture is choice. systems are stories.”_
