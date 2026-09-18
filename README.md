# inku — Ink & Margin

Business plan for importing and selling Japanese stationery in Bangladesh.

## Deploy

```bash
npx vercel --prod
```

Static site, no build step. Vercel serves `index.html` at `/`.

## Files

| File | What it is |
|---|---|
| `index.html` | The manual: 16 sections, 20 diagrams, live ROI model |
| `bg.jpg` | Background photograph |
| `logo.svg` | Square mark — nib in a wax seal. SVG favicon, avatar, app icon |
| `wordmark.svg` | Horizontal lockup with tagline |
| `favicon.ico` | Multi-size ICO (16/32/48) |
| `favicon-16/32/180/192/512.png` | Raster icons. 180 = Apple touch, 512 = PWA |
| `manifest.webmanifest` | PWA manifest |
| `vercel.json` | Long cache headers on static assets |

## Brand

- **inku** — インク, the Japanese word for ink. Four letters, two syllables.
- Indigo `#2B3A67` · seal red `#C1452F` · off-white `#F9F8F5`
- Shippori Mincho (display) · IBM Plex Sans (body) · IBM Plex Mono (data)

`index.html` carries `noindex, nofollow`. Remove that meta tag to make it public.
