# Three Fat Babies Website

Source for the Three Fat Babies website — hand-painted custom pet portrait
frames, made in memory and for the pets still here.

## Where things are

| Path | What it is |
|---|---|
| `index.html` | Home — opening line, then the portrait frames, then why we make them |
| `portraits/` | All three commissions, all eleven photographs |
| `babies/` | Pei, Moo and Cata |
| `contact/` | Email, Instagram, and how to commission a portrait |
| `assets/` | Shared images + `site.css`, the one stylesheet every page uses |
| `CONTENT.md` | **Single source of truth** for copy, product facts and tone rules |
| `unorganized material/` | Drop zone for new material ([how it works](unorganized%20material/README.md)) |

Plain static HTML with one shared stylesheet. No build step, no dependencies
beyond Google Fonts.

## The product

**Custom pet portrait frames** — a three-dimensional portrait that leans out of
an ornate frame, the pet's name in gold across the top. Each one is **painted by
hand** and **customised to one animal** from photos the customer sends.

Made most often **as memorials**, and also for pets who are still here.

Two rules live in `CONTENT.md` and matter more than anything else on this site:

1. **Never claim what the piece is made of** — not sculpted, not carved, not
   wood, not resin. Say hand-painted and customised.
2. **No grief clichés and no urgency.** Warm, plain, short. Grief is not a
   conversion funnel.

The earlier **Café Crust fridge magnets** are retired and appear nowhere. The
**Meet Our Humans** section was removed. Both are preserved in `../archive/`.

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

GitHub Pages, `main` branch, root folder.
