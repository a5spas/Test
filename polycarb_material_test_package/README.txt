POLYCARBONATE MATERIAL TEST

Files:
- index.html: Three.js material test viewer
- polycarb_clear.glb: supplied sidewall model
- ral_7024.jpg and ral_9001.jpg: supplied colour reference maps

To test:
1. Put all files in the same folder.
2. Run a local web server from that folder (for example, in the folder run: python -m http.server 8000).
3. Open http://localhost:8000 in a modern browser.

The viewer loads Three.js modules from jsDelivr, so an internet connection is required.
The four new material presets are starting points and need comparison/tuning against physical samples and reference images. The supplied RAL images are included as references; the current presets use their sampled solid colours rather than loading them as maps.
