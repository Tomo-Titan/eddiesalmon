# eddiesalmon.com

A one-page, mostly-true cinematic retrospective of Eddie Salmon's early YouTube career
(the **Stencil25 Studios** archive) — built as a wedding best-man gag.

Visitors who've just heard the speech land here and are greeted with confetti, a marquee,
and Eddie's two restored masterpieces presented like prestige films:

- 🚗 **Evil Car** — `https://www.youtube.com/watch?v=JpMAVFLZBUg`
- 🍔 **"I'm Not Fat!"** — `https://www.youtube.com/watch?v=x7eRDTIRbe8`
- 📺 The channel — `https://www.youtube.com/@stencil25`

## Stack

A single static `index.html`. No build step, no dependencies. Fonts via Google Fonts;
videos via click-to-play YouTube embeds; confetti via a tiny inline `<canvas>` script.

## Deploy

Hosted on Vercel, domain on GoDaddy DNS.

```bash
vercel --prod   # ship to production
```

## Editing

It's one file. Open `index.html`, change the words, save, run `vercel --prod` again.
