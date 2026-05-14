# WordPress handoff — Doe v. SBUSD case page

This folder is everything you need to bring the case microsite into the existing veenfirm.com WordPress build. The full standalone version lives at the repo root (`index.html`) for reference, but for WP you only want the content sections from this folder.

## Files

- `content.html` — the body content of the page, in the order it should appear. Hero, case overview, what happened, case facts, arrests strip, timeline, contact + intake form, press materials, additional resources, CTA. No `<html>`, `<head>`, `<body>`, no top nav, no site footer.
- `disclaimer.html` — the legal disclaimer paragraph that needs to render at the bottom of the case page (above or inside the existing site footer). Required for CRPC 7.1 / B&P 6158.1 cover.
- This README.

## Important

- The standalone version already uses the veenfirm.com theme classes (`page-section`, `bg-dark`, `bg-mostlydarktowhite`, `col-sm-4`, `headerbrah`, `whiteparent`, `whiteparentlink`, `contactleft`, `socialicons`, etc.). When pasted into a WP page that uses the same mega-theme, the styles should resolve automatically. No new CSS to add.
- Font Awesome icons (`<i class="fa-sharp fa-solid ...">`) are already loaded by the theme. If any icons render as blank squares, confirm the theme's Font Awesome kit is the Pro/Sharp kit.
- The intake form is a Typeform embed. The form ID is `01KEW0QR6609J0H84M4104VKW1` and the popup buttons use `orBbLa5B`. The embed script is `https://embed.typeform.com/next/embed.js`. If the theme doesn't already load Typeform's embed script globally, add it to this page only.

## Suggested WP page setup

1. Create a new WP page titled something like "Doe v. Santa Barbara Unified School District". Slug: `/sexual-assault` or `/cases/doe-sbusd` (Adam's call).
2. Set the page template to the "no sidebar / full width" template the rest of the case pages use.
3. Add a single Custom HTML block (or whatever the theme's raw-HTML block is) and paste the contents of `content.html` into it.
4. Add the contents of `disclaimer.html` either as a second Custom HTML block at the bottom of the page, or include it in the theme footer for this template if there's an existing slot.
5. If the theme runs `wpautop` and breaks the markup, disable it for this page (most easily via a block-based page or with a snippet like `remove_filter('the_content', 'wpautop')` for this template).
6. Two PDFs are linked from the press materials section: `complaint.pdf` and `press-release.pdf`. Adam will give you the final file-stamped PDFs separately. Upload to Media and update the two `href`s in `content.html` before publish.

## Links to verify before publishing

The page references the following internal veenfirm.com URLs. Confirm each one resolves on production WP:

- /attorneys/anthony-label/
- /attorneys/steven-kronenberg/
- /attorneys/bryan-ceglio/
- /practice-areas/ (and the various practice-area children listed in the footer of the standalone)

If any are wrong, send them back to Adam and he'll fix.

## Compliance notes (don't strip these)

- The disclaimer paragraph is not decorative. It needs to be on the page.
- Don't add testimonials, dollar figures, guarantees, or anything that reads as a promise of outcome. The current copy is intentionally conservative.
- The defendants are named in the complaint and in the Sheriff's public release. The page sticks to those sources. Don't add additional characterizations of the defendants beyond what's in the existing copy.

## Questions

Ping Adam directly: adam@planet10b.com.
