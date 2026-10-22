# Neeharam · Housewarming Invitation

**Housewarming of Vineeth & Aparna · Neeharam**
Saturday, 02 January 2027 · 4:00 PM onwards

A single-file, modern housewarming invitation with a South Indian (Kerala) aesthetic —
nilavilakku brass lamps, a mango-leaf *toran*, a *kalasham*, jasmine and marigold
petals, kolam motifs, and the Malayalam name of the rite (ഗൃഹാരോഹണം · *Grihaarohanam*).

## Live site

https://cntrlx.github.io/vineeth-housewarming/

## What's inside

- `index.html` — the entire invitation. All CSS and JavaScript are inlined; no build step,
  no runtime dependencies beyond the Google Fonts stylesheet.
- `assets/og.jpg` — 1200×630 link-preview image (WhatsApp, Telegram, X, iMessage).
- `assets/invitation-card.png` — 1080×1350 shareable invitation card.
- `assets/favicon.svg` — the house mark.

## Features

- **Cover screen** with an arch, the names, the date and an animated brass lamp.
- **Day / night themes**, remembered in `localStorage`, with a matching `theme-color`.
- **Live countdown** to 02 January 2027, 4:00 PM IST.
- **Venue map** (Google Maps embed) with one-tap directions.
- **Add to calendar** — a Google Calendar link and a generated `.ics` file for
  Apple/Outlook, with a one-day-before reminder.
- **RSVP** — pick yes / maybe / can't make it, then send the ready-made message on
  WhatsApp or copy it. The choice persists on the device.
- **Share** — native share sheet, WhatsApp share, and copy-to-clipboard.
- **Print stylesheet** — prints as a clean one-page invitation.
- Responsive down to small phones, with a sticky action bar (directions / calendar / share).
- Reduced-motion and keyboard-accessible throughout.

## Regenerating the images

The share images are rendered from HTML so they always match the site:

```bash
chromium --headless --disable-gpu --no-sandbox --hide-scrollbars \
  --window-size=1200,900 --virtual-time-budget=15000 \
  --screenshot=og-tall.png render/og-only.html
# crop to 1200x630, then convert to og.jpg
```

## Details

| | |
|---|---|
| Hosts | Vineeth & Aparna |
| Home | Neeharam (നീഹാരം) |
| Rite | Grihaarohanam (ഗൃഹാരോഹണം) |
| Date | Saturday, 02 January 2027 |
| Time | 4:00 PM onwards |
| Venue | Neeharam — 11.2950106° N, 75.8949568° E |
