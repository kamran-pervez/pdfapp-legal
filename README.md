# EdifyPDF — Legal pages

Public Privacy Policy and Terms & Conditions for **EdifyPDF**.

This repo is separate from the private app source so GitHub Pages can stay free.

## Pages

| Page | File |
|------|------|
| Home | [index.html](index.html) |
| Privacy Policy | [privacy.html](privacy.html) |
| Terms & Conditions | [terms.html](terms.html) |

## Enable GitHub Pages

1. Push `main` to GitHub.
2. Open the repo on GitHub → **Settings** → **Pages**.
3. **Source:** Deploy from a branch.
4. **Branch:** `main` / folder: `/` (root) → Save.
5. Wait a minute, then open:
   - https://kamran-pervez.github.io/pdfapp-legal/
   - https://kamran-pervez.github.io/pdfapp-legal/privacy.html
   - https://kamran-pervez.github.io/pdfapp-legal/terms.html

## App wiring

In the EdifyPDF app, set:

- Privacy: `https://kamran-pervez.github.io/pdfapp-legal/privacy.html`
- Terms: `https://kamran-pervez.github.io/pdfapp-legal/terms.html`

## Before store release

1. Optionally set a specific governing-law country in `terms.html`.
2. Update the Privacy Policy again if you enable Crashlytics or other network services.

These pages are written for EdifyPDF’s current on-device design. They are not legal advice; have them reviewed if you need formal counsel.
