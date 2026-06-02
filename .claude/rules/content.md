---
paths:
  - "index.html"
---

# Content & Features

## Page Sections (in order)

1. **Hero** — Full-viewport Spline 3D scene, headline, scroll indicator, spotlight beam
2. **Ticker** — Horizontal marquee of marketing capabilities
3. **Stats Bar** — 4 key metrics (impressions, projects, community, campaigns)
4. **About** — Bio + facts grid
5. **Work** — Project cards (see below)
6. **Media** — Embedded videos (Bongo Promo, GUB Promo)
7. **Skills** — 9 skill tiles
8. **Contact** — Email + Twitter CTA
9. **Footer** — Nav links + copyright

## Interactive Features

- Custom cursor (dot + ring, enlarges on link hover — hidden on touch devices)
- Terminal widget (top-right) — live clock, browser info, click counter, scroll depth
- Language switcher (EN, ES, ZH, RU, FR) with localStorage persistence
- "Degen mode" toggle — enhanced visual effects
- SOL price ticker via Binance WebSocket API (real-time, colour-coded)
- Back-to-top button (appears > 500px scroll)
- Mobile hamburger menu (activates < 900px)
- Canvas caustic water animation
- Click-triggered bubble particles
- Copy-to-clipboard on contract addresses
- Easter egg: hidden treasure chest (bottom-right area, links to YouTube)

## Project Cards

Each card contains:
- Name + status badge: `Rugged` / `Active` / `On Ice` / `Ended` / `Coming Soon`
- ATH market cap figure
- Description with highlighted metrics
- Solana contract address + copy button (where applicable)
- External links (Twitter, website)
- Pulsing dot indicator on active projects

Current projects: DoopApp, LORE.Vision, Tampon Tim, Clipped.fun, Gently Used Blunt, Bongo, PTSD, Confidential (NDA).

## i18n

Translations are hardcoded in a JS `translations` object. Text elements use `data-i18n` attributes. Language preference persists via `localStorage`. To add a language: add an entry to `translations` and a button to the language switcher UI.
