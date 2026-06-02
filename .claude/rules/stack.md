# Stack & Structure

## Architecture

Single-file static site — everything lives in `index.html`. No build step. No package.json. No node_modules.

```
JAWS Website/
├── index.html          # All HTML, CSS, and JS (~1,000 lines)
├── GUB.jpg             # Project portfolio image
├── Bongo Promo.mp4     # Media section video
├── GUB promo.mp4       # Media section video
├── vercel.json         # Vercel routing config (SPA fallback)
└── test.txt            # Scratch file (ignorable)
```

## Deployment

Push to the main branch — Vercel auto-deploys on commit. No build command needed.

## External Dependencies (CDN/API only — no npm)

- `@splinetool/viewer@1.9.82` — 3D hero scene (loaded via `<script type="module">`)
- Google Fonts — Bebas Neue, JetBrains Mono
- Binance WebSocket API — SOL/USDT price feed
- `unavatar.io` — Twitter avatar images
