# Kalam & Kami — Ink & Margin

Private business plan for importing and selling Japanese stationery in Bangladesh.

## Deploy to Vercel

```bash
npx vercel          # preview
npx vercel --prod   # production
```

Static site — no build step, no framework. Vercel serves `index.html` at `/`.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole manual: 16 sections, 17 diagrams, live ROI model |
| `bg.jpg` | Background photograph |
| `logo.svg` | Square logo — nib in a wax seal. SVG favicon, avatar, app icon |
| `wordmark.svg` | Horizontal lockup with tagline, for a site header |
| `favicon.ico` | Multi-size ICO (16/32/48) |
| `favicon-16/32/180/512.png` | Raster icons. 180 is Apple touch, 512 is the PWA manifest |
| `manifest.webmanifest` | PWA manifest |
| `vercel.json` | Long cache headers on static assets |

## Brand

- Name: **Kalam & Kami** — কলম (pen, Bangla) + 紙 / kami (paper, Japanese)
- Indigo `#2B3A67` · seal red `#C1452F` · off-white ground `#F9F8F5`
- Type: Shippori Mincho (display) · IBM Plex Sans (body) · IBM Plex Mono (data)

`index.html` carries `noindex, nofollow` — remove that meta tag if you ever want it public.
