# CV - PDF Generation Guide

This folder contains:

| File | Purpose |
|------|---------|
| `saeed-turabzadeh-cv.html` | Website-integrated CV page (with site header, nav, footer) |
| `saeed-turabzadeh-cv-print.html` | Standalone CV (clean layout, used for PDF generation) |
| `saeed-turabzadeh-cv.pdf` | Downloadable PDF version of the CV |

## How to Update the CV

### 1. Edit the content

Make your changes in **`saeed-turabzadeh-cv-print.html`** (the standalone version). This is the single source of truth for CV content.

Then apply the same content changes to **`saeed-turabzadeh-cv.html`** (the website version) so the online page stays in sync.

### 2. Regenerate the PDF

From the repository root directory, run:

```bash
cd cv && google-chrome --headless --disable-gpu --no-sandbox \
  --print-to-pdf=saeed-turabzadeh-cv.pdf \
  --no-margins \
  "file://$(pwd)/saeed-turabzadeh-cv-print.html"
```

Alternatively, open `saeed-turabzadeh-cv-print.html` in a browser and use `Ctrl + P` → Save as PDF.

### 3. Verify

Open the generated `saeed-turabzadeh-cv.pdf` to confirm it looks correct before pushing.

## Important Notes

- **Always** generate the PDF from `saeed-turabzadeh-cv-print.html`, not from the website version.
- The website version (`saeed-turabzadeh-cv.html`) includes site navigation and a floating download button that links to `saeed-turabzadeh-cv.pdf`.
- The download button triggers a file save dialog for visitors.
