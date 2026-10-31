# Stitched Up 🧶

A browser-based crochet project tracker and colourwork design studio.

## Features
- Import written crochet patterns by pasting text or selecting a readable PDF.
- Mark instructions complete, collapse earlier rows, jump to the current row.
- Track projects, notes, status, and a separate +1/+5/+10 / −1/−5/−10 row counter.
- **Pattern Planner** (new):
  - **Granny square planner:** create reusable multicolour square designs (up to five colour rounds), duplicate/edit/delete them, and arrange them in an adjustable blanket grid. Click to paint, tap two cells to swap, or drag and drop on desktop.
  - **Tapestry/mosaic planner:** choose a stitch-by-row grid size, use a colour palette or custom colours, draw with the pencil, create rectangles by choosing opposite corners, fill a region, erase, swap cells, and undo recent colour changes.
  - **Image to Crochet Chart:** upload PNG/JPG/WebP/GIF images, set stitch width and row height (up to 150 × 150, max 12,000 cells), adjust a 2–24-colour pixel-art slider, simplify tiny colour details (Off to Very strong), use a one-click crochet-friendly preset with a smaller size and five colours, optionally lock the original aspect ratio, and inspect original versus pixelated previews. Apply the result as an editable chart.
  - **Existing gridded chart:** enable grid-line removal to sample the centre of each evenly spaced cell instead of importing dark lines. Enter the correct original stitch dimensions; it may require manual clean-up if lines are thick, slanted, or misaligned.
  - Toggle the stitch grid on/off and export a finished layout as a PNG, with or without grid lines. Save multiple designs.

## Publish with GitHub Pages
1. Create a GitHub repository, or open your existing `stitched-up` repository.
2. Upload/replace the `index.html` file at the repository root. You can also add this README and `.nojekyll`.
3. Commit changes.
4. Under **Settings → Pages**, select **Deploy from a branch → main → /(root)** and save.
5. Visit your GitHub Pages link once deployment finishes.

## Storage and limitations
- Projects and planner designs are saved **locally in this browser**. They do not automatically sync across devices, and clearing site data can erase them.
- The existing **Export backup** feature backs up an individual tracker project; it does **not** include planner designs. Planner designs can be exported as PNG images, but PNG files cannot be re-imported as editable layouts.
- The PDF importer extracts selectable PDF text in-browser and may not read scanned or complex PDFs perfectly.
- Image conversion happens locally in the browser. A colour-reduced chart is a visual starting point, and yarn colours, details and grid removal may need manual adjustment.
- The colourwork planner creates visual charts, not written stitch-by-stitch mosaic crochet instructions. Granny designs are a stylised colour preview rather than an exact stitch diagram.
- Internet access is needed to load the PDF parsing library and optional web fonts.
