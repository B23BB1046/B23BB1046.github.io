# Barcode Marker AR Demo

A small browser-based augmented-reality experiment using A-Frame and AR.js. The page opens the webcam, detects a barcode marker, and renders a simple 3D sphere when marker value `246` is recognized.

## File
- `barcode.html` — AR scene, webcam marker detection, and sphere rendering.

## Run locally
Serve the file through a local HTTP server and open it in a browser that supports webcam access. Grant camera permission when prompted. Camera access may not work when opening the HTML directly from the filesystem; use localhost or HTTPS.

## Notes
- The demo depends on external A-Frame and AR.js scripts.
- Test camera permissions and browser compatibility before presenting the project.
- For a production-ready demo, pin maintained library versions and document the marker pattern.