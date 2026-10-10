# Luv or Pop — Portfolio (Astro)

## Run locally
```
npm install
npm run dev      # http://localhost:4321
npm run build    # static site → dist/
```

## Deploy
Push this folder to GitHub, then import it on Vercel or Netlify (framework preset: Astro). No settings needed.

## Structure
- `src/pages/index.astro` — the page; builds to static HTML.
- `src/design/PortfolioHero.html` — the page markup, styles and scroll/animation logic.
- `public/assets/` — images (webp + png fallbacks).
- `public/support.js` — component runtime the page uses.

## Updating
Re-export `Portfolio Hero.dc.html` from the design project and replace `src/design/PortfolioHero.html`.
