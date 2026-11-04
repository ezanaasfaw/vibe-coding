# Project: Pixel Art Studio

> - **Files:** pixel_art.html
> - **Dates:** 2026-11-04 → 2026-11-04
> - **Defaults:** Claude (claude.ai chat) · Sonnet 5.5
> - **Status:** prototype
> - **Use:** none yet
> - **Reusability:** artifact medium · prompt pattern medium
> - **Tags:** single-file-html, export-import, localStorage
> - **Takeaway:** Worked on the first try from a short, specific prompt.
> - **Story value:** none
> - **Surprises:** The app idea was chosen by me. It worked with no fixes needed.

# Prompt 1 (build the first version):

> - **Tool:** Claude (claude.ai chat) · Sonnet 5.5 · 2026-11-04
> - **Session:** fresh · attached: none
> - **Verified:** human-tested
> - **Human edits:** none

Build a single-file HTML pixel art editor with a 16x16 canvas. Tools: pencil, eraser, fill bucket, and color picker. Give me a 16-color palette plus a custom color input, a mirror-drawing toggle, a grid toggle, undo, and clear. Let me download my art as a PNG with a transparent background, and autosave to the browser. No external libraries.

## Output 1:

I built the Pixel Art Studio app based on your prompt. I haven't run it myself, so you'll need to test it to make sure everything works correctly.
- Pixel Art Studio (pixel_art) is a single-file HTML app with a 16×16 canvas where you can create pixel art.
- Drawing Tools: The app includes a pencil, eraser, fill bucket, and color picker.
- Color Options: You can choose from a 16-color palette or use a custom color picker.
- Additional Features: Mirror drawing, grid toggle, undo, and clear options make editing easier.
- PNG Download: You can export your artwork as a PNG with a transparent background.
- Autosave: Your artwork is automatically saved in the browser, so you can continue working on it later.
- Design: The interface is simple and organized, with easy-to-access drawing tools and color options.
Steps from here:
1. Unzip. Download pixel_art.zip, right-click it, and choose Extract All. You'll get a folder containing the HTML file and a prompts.md file.
2. Move it in. Drag the pixel_art folder into your vibe-coding folder.
3. Test the app yourself. Double-click the HTML file to open it in your browser and try the following:
   - Pencil: Select a color and draw on the canvas.
   - Eraser: Remove pixels and check that they become transparent.
   - Fill Bucket: Fill an enclosed area with a selected color.
   - Color Picker: Click an existing pixel to select its color.
   - Mirror Mode: Turn on mirror drawing and check that your strokes appear symmetrically.
   - Grid Toggle: Turn the grid lines on and off.
   - Undo: Draw something and undo the last action.
   - Clear: Clear the entire canvas and make sure all pixels are removed.
   - PNG Download: Download your artwork and verify that the background is transparent.
   - Autosave: Refresh the browser and check that your drawing is still there.
Note: Browser autosave uses local storage, so your artwork will generally remain saved in the same browser unless you clear its stored data.