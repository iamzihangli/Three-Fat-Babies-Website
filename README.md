# Three Fat Babies Website

Source for the Three Fat Babies website — Pei, Moo, Cata, and Mama's
hand-sculpted custom pet portrait frames.

## Where things are

| Path | What it is |
|---|---|
| `index.html` | Design chooser — links to all five candidate designs |
| `versions/v1-storybook/` | Warm, playful, children's-book feel |
| `versions/v2-atelier/` | Espresso + cream boutique editorial |
| `versions/v3-scrapbook/` | Polaroids, washi tape, handwritten captions |
| `versions/v4-gallery/` | Museum minimal, huge whitespace |
| `versions/v5-bento/` | Pastel bento grid, modern and app-like |
| `assets/` | Shared, web-optimised images used by every version |
| `CONTENT.md` | **Single source of truth** for all copy and products |
| `unorganized material/` | Drop zone for new material ([how it works](unorganized%20material/README.md)) |

Each version is one self-contained HTML file with inline CSS and JS. No build
step, no dependencies beyond Google Fonts.

## Choosing one

Open `index.html`, look at all five, then keep the winner. To ship it, move the
chosen version's `index.html` to the repo root (fixing the `../../assets/` paths
to `assets/`) and delete `versions/`.

## Current product

**Custom 3D pet portrait frames** — hand-sculpted, hand-painted, the pet leaning
out of an ornate frame with their name in raised gold lettering. Made to order
from customer photos. Commissions shown: Peggy, Perdita, Pongo.

The earlier **Café Crust fridge magnets** are retired and appear on no version.
Their photos and the original Google Sites pages are preserved in `../archive/`.

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

GitHub Pages, `main` branch, root folder.
