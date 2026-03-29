# escher-laptop-loop

Browser-based editor for turning a single image into an Escher-style infinite-zoom still.

## Run locally on macOS

1. Clone/download this repo.
2. Open `escher.html` directly, or run:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## How to escherify one image

1. Upload your image.
2. Drag the 4 red corner points to the portal/window/screen area where the recursive image should appear.
3. Increase **Zoom steps** and tune **Fade per layer** until it looks right.
4. Use numeric corner coordinates for precise tweaking (live updates).
5. Download the final PNG.
