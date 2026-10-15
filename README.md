# Profile Frame Maker

A small web page that adds a curved text banner to a profile picture — type any text, pick colors, position the photo, download a PNG.

Everything runs in the visitor's browser. Photos are never uploaded anywhere.

## Features

- Upload, or drag and drop, a photo
- Drag to position; scroll wheel, pinch, or the slider to zoom
- Banner text, font, text size, letter spacing, text color and shadow
- Two-color gradient banner with adjustable thickness, length and position (bottom, sides or top)
- Download as a 1000 × 1000 PNG
- "Share image" button on browsers that support sharing files (mostly mobile)
- "Copy link to this frame" saves the current banner settings into the URL, so you can send people a link that opens with your text and colors already set

## Customizing

- **Default text and colors:** change the `value="..."` attributes on the inputs in `index.html` (for example `id="text"`, `id="c1"`, `id="c2"`).
- **Fonts:** the page loads Poppins and Montserrat from Google Fonts. To add another, add it to the Google Fonts `<link>` and add an `<option>` to the `font` select.
- **Output size:** change `SIZE` (currently 1000) near the top of the script.
