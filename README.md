# Stitched Up 🧶

A browser-based crochet pattern and project tracker.

## Features
- Paste crochet pattern text or import a PDF with selectable text.
- Review and edit imported instructions.
- Expand repeat ranges into individually checkable rows.
- Tick off completed rows and keep progress per project.
- Stitch/row counter buttons: **−10, −5, −1, +1, +5, +10**.
- Keep project notes, yarn and hook details, and project statuses.
- Export/import project backups in JSON format.

## Publish with GitHub Pages
1. Create a new **public** repository on GitHub, e.g. `stitched-up`.
2. Use **Add file → Upload files** and upload `index.html`, `README.md`, and `.nojekyll` **from this folder** (not the ZIP itself).
3. Commit the files to the `main` branch.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, `main`, and `/(root)`, then save.
5. Once GitHub Pages deploys, visit `https://YOUR-USERNAME.github.io/stitched-up/`.

You can also download this ZIP, extract it, and upload the extracted files through GitHub's web interface. To update the site later, replace `index.html` in the same repository.

## Important notes
- Data is stored **locally in each browser**. GitHub Pages does **not** sync projects between devices. Use the app's JSON backup export/import to transfer progress.
- PDFs are read in your browser using PDF.js loaded from a CDN; an internet connection is required. Scanned PDFs without selectable text aren't supported automatically.
- Text interpretation is rule-based, not AI; always review imported pattern rows for correctness.
- Do not publish copyrighted paid pattern text in the repository. Your pattern and project data stays in browser storage, not in the GitHub source files.
