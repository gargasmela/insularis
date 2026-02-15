# Band images

Place your photos here. The site expects:

- **hero.jpg** — used as the main hero background (landscape works best)
- **group.jpg** — featured band group photo in the Media section (best group shot)
- **band.jpg** — band portrait for the gallery
- **live.jpg** — live/on-stage shot for the gallery

Supported formats: `.jpg`, `.jpeg`, `.png`.

After adding images, run from project root:

```bash
npm run metalize
```

This generates metal-styled versions in `pics/processed/` (desaturation, contrast, slight vignette). The site uses the processed images when available.
