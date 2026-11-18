# Elizabeth Koleva — CV website

Static CV page for GitHub Pages.

- `index.html` — the CV as a web page, with a toggle to preview the PDF, download menu, QR code (with PNG download) and print.
- `cv/Koleva_Elizabeth_CV.pdf` — current CV (2 pages).
- `cv/Koleva_Elizabeth_CV_extended.pdf` — extended CV (3 pages: conferences, volunteering).

To update the CV: replace the PDF(s) in `cv/` with the same file names, edit the text in `index.html`, commit and push.
The QR code is generated in the browser from the page's own URL, so it always points to wherever the site is hosted.
`index.html#pdf` opens straight into the PDF view.
