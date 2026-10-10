# MoizPDF Tools — Complete browser-based PDF toolkit

## Tools
- Merge multiple PDFs; reorder files before merging
- Split a PDF into individual page PDFs inside a ZIP
- Extract selected pages
- Delete selected pages
- Rotate every page
- Convert pages to PNG/JPG images in a ZIP
- Re-save/optimize PDFs (file-size reduction is not guaranteed)
- Drag-and-drop, remove/clear files, responsive mobile UI, dark mode

## Run locally
Extract the ZIP and open `index.html` in a modern browser. Internet access is needed to load PDF-Lib, PDF.js and JSZip from CDNs. Use copies of important documents when testing.

## Deploy once to GitHub + Vercel
Upload `index.html`, `styles.css`, `app.js`, and `README.md` to one GitHub repository. Import that repository into Vercel, select **Other** framework preset, leave the build command blank, set output directory to `.` and deploy. Vercel will provide the real live URL. `moizpdf-tools.vercel.app` is only possible if the name is available.

## Limitations
Browser-only optimization does not recompress embedded images and cannot guarantee a smaller PDF. Large PDFs can consume substantial RAM. Password-protected/encrypted PDFs, unusual PDF structures, and some fonts may fail. PDF-to-image conversion of long PDFs can use substantial memory. Dependencies are loaded from public CDNs, so an internet connection is required. Files are processed in the browser; this static site has no upload backend.
