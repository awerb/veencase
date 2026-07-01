# The Veen Firm Press Room

A single-page newsroom for The Veen Firm LLP: recent cases in the news, press releases, media contacts, attorney photos, and a downloadable press kit. Built in the firm's design system (Montserrat, ink and wine, a single accent).

## Files

- `index.html` — the press room page. Self-contained; no build step.
- `assets/press-releases/` — branded PDFs of the three released stories (Tesla, Santa Barbara, Whitehead).
- `assets/fact-sheet/` — one-page firm fact sheet PDF.
- `assets/img/` — firm logos, plus high-res attorney headshots used in the press kit.
- `Veen-Press-Kit.zip` — the full kit (photos, logos, releases, fact sheet) for download.
- `Media-Coverage-Master-List.md` — the verified list of every coverage link, by case.

## Notes

- Attorney headshots and the hero photo load live from `veenfirm.com/wp-content/themes/mega-theme/images/`. On the firm's own site these are same-origin. If those theme files are ever renamed, update the `src` URLs in `index.html`. High-res copies are bundled in the press kit zip as a backup.
- Each case links to its blog post on veenfirm.com. Coverage links open in a new tab.
- Attorney photography by Julio Duffoo, free for Veen Firm media use.

## Deploy

Open `index.html` directly, or publish the folder to any static host. For GitHub Pages, `index.html` at the repo root serves at the site root.

## Legal

Informational only, not legal advice. Prior results do not guarantee a similar outcome.
