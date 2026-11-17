# Bollywood Cafe Ooty, website

Single-page website for **Bollywood Cafe**, a small tea & coffee shop on Segur Rd, Ooty (4.9★, #4 of 136 coffeehouses in Ooty).

- `public/index.html`: the whole site (HTML + CSS + JS; GSAP animations loaded from cdnjs)
- `BUSINESS_ANALYSIS.md`: internal business strategy and pain-point analysis (kept out of `public/` so it is **not** served on the live site)

## Run locally
```bash
python -m http.server 8765 --directory public
```
Then open http://localhost:8765.

## Deploy
Render static site: no build step, **publish directory `public`**. Only files inside `public/` go live.

## Before going live
- Replace the Unsplash placeholder photos with the cafe's own photos
- Confirm menu prices with the owner
