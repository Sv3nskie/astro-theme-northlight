# Northlight — Astro theme

A cinematic, scroll-driven one-page theme for **agencies, consultancies and studios**. Dark, fast, and built with plain CSS and a single vanilla JS file — no UI framework, no animation library.

**[Live demo →](https://sv3nskie.github.io/astro-theme-northlight/)**

## Features

- **Scroll choreography that rewinds.** Pinned chapters (a stacked services deck, a horizontal statement, client stories), word-by-word lighting, parallax and a 3D plate stack — all driven by scroll position, so everything plays backwards on scroll-up.
- **Intro curtain** on first visit (once per session; add `?intro` to replay).
- **Custom cursor, magnetic buttons, logo marquee, animated counters.**
- **Fully responsive** with a full-screen mobile menu and `svh`-based pinning so mobile browser bars never hide content.
- **Accessible:** respects `prefers-reduced-motion` (everything renders in its final state), skip link, semantic landmarks.
- **Zero dependencies** beyond Astro.

## Getting started

```bash
npm create astro@latest -- --template Sv3nskie/astro-theme-northlight
cd <your-project>
npm run dev
```

## Make it yours

| What | Where |
| --- | --- |
| Brand name, contact details, SEO title/description, share image | `src/config.ts` |
| Section copy and images | `src/components/*.astro` (one file per section) |
| Colors, type and spacing tokens | `src/styles/nocturne.css` |
| Layout and animation states | `src/styles/main.css` |
| Scroll/pointer behaviour | `src/scripts/main.js` |

The brand name drives the logo, the intro curtain and the big footer wordmark automatically.

Placeholder photography is from [Unsplash](https://unsplash.com) — replace it with your own before launch.

## Deploying

Any static host works (`npm run build` → `dist/`). The included GitHub Actions workflow publishes the demo to GitHub Pages.

## Credits

Designed and built by **[Sven Esser](https://sv3n.dev?utm_source=github&utm_medium=theme-readme&utm_campaign=northlight)** — full-stack & Web3 developer. Need a custom site? [Get in touch](https://sv3n.dev/contact?utm_source=github&utm_medium=theme-readme&utm_campaign=northlight).

MIT licensed. Keeping the small "Theme by Sv3n" credit in the footer is appreciated but not required.
