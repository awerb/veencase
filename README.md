# Doe v. Santa Barbara Unified School District — case microsite and press materials

Working repository for the case microsite and press materials supporting the filing of *Doe v. Santa Barbara Unified School District, et al.* on May 13, 2026, with public launch scheduled for Monday, May 18, 2026.

## Structure

```
.
├── index.html                                     # Case microsite (single-file, uses veenfirm.com stylesheets)
├── press/
│   ├── press-release-FACTUAL-prnewswire.docx      # Wire release for PR Newswire distribution
│   ├── press-release-NARRATIVE-reporters.docx     # Direct-to-reporter narrative version
│   ├── media-plan.docx                            # Rollout plan, reporter strategy, risk matrix
│   └── press-contacts.xlsx                        # 54-contact press list with pitch order, email patterns, community voices
└── README.md
```

## Microsite notes

- Single-file HTML. Pulls live CSS and fonts from `veenfirm.com/wp-content/themes/mega-theme/css/` and Adobe Typekit `xgz5rzp.css`.
- Intake form: Typeform inline embed `01KEW0QR6609J0H84M4104VKW1` plus popup buttons using `orBbLa5B`. Embed script loaded from `https://embed.typeform.com/next/embed.js`.
- Color palette is strictly veenfirm: `#83201e` burgundy, `#161920` near-black, `#ededf5` panel, `#494b50` body, `#d0d3da` rule.
- Expects two PDFs to be added at the repo root for the press materials section to link correctly:
  - `complaint.pdf` (file-stamped complaint)
  - `press-release.pdf` (the wire release exported to PDF)

## Spokesperson protocol

Steven A. Kronenberg and Anthony L. Label are the firm's authorized spokespersons and are responsible for the press release. The plaintiff and his family are not available for press.

Press line: (510) 560-6731
Press email: info@veenfirm.com

## Confidentiality

This repository contains pre-launch materials. Do not distribute or make public before the launch date.
