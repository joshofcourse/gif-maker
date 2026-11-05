# GIF Maker

A lightweight, single-file GIF creator that runs entirely in the browser. Nothing is uploaded.

Live at https://joshofcourse.github.io/gif-maker/ — or open `index.html` locally.

- Upload images, drag to reorder, duplicate, remove, reverse
- Per-frame timing (or set all at once) with live preview
- Loop forever, once, or N times
- Export at preset/custom widths and aspect ratios (contain / cover / stretch)
- Compression: colour count, shared vs per-frame palette, quality, dithering, frame skipping

Encoding uses [gifenc](https://github.com/mattdesl/gifenc), loaded from jsDelivr.
