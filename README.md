# The Veen Firm Press Room

A single-page newsroom for The Veen Firm LLP: recent cases in the news, press releases, media contacts, attorney photos, and downloadable media assets. Built in the firm's design system (Montserrat, ink and wine, a single accent).

## Files

- `index.html` — the press room page. Self-contained; no build step.
- `video-room.html` — broadcast TV coverage (24 station reports), linked from the press room.
- `careers.html` — the careers page (open roles, culture, how to apply).
- `assets/press-releases/` — branded PDFs of the four released stories (Musto charges, Tesla, Santa Barbara, Whitehead).
- `assets/fact-sheet/` — one-page firm fact sheet PDF.
- `assets/img/` — firm logos and the social share card.
- `assets/img/headshots/` — attorney portraits in `web/` (1200px) and `print/` (full-resolution) versions, from the 2025–26 Julio Duffoo shoot. Bryan Ceglio is web-only (no print-res file supplied).
- `Media-Coverage-Master-List.md` — the verified list of every coverage link, by case.

## Notes

- Attorney portraits are served locally from `assets/img/headshots/` with per-attorney web and print download buttons. Only the masthead background photo still loads from `veenfirm.com/wp-content/themes/mega-theme/images/` (same-origin on the firm's own site).
- Each case links to its blog post on veenfirm.com. Coverage links open in a new tab.
- Attorney photography by Julio Duffoo, free for Veen Firm media use.

## Deploy

Open `index.html` directly, or publish the folder to any static host. For GitHub Pages, `index.html` at the repo root serves at the site root.

## Legal

Informational only, not legal advice. Prior results do not guarantee a similar outcome.
