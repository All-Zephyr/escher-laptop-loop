# escher-laptop-loop

Browser-based editor for creating an Escher-style recursive laptop image.

## Run locally on macOS

1. Clone/download this repo.
2. Open `escher.html` directly, or run:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## How to use the recursive editor

1. Upload your base image.
2. Drag the 4 red corner points to match the laptop screen area in the image.
3. Tweak recursion depth and fade until the loop looks right.
4. Fine-adjust exact corner coordinates in the numeric boxes (live updates).
5. Download PNG when you like the result.

This is designed specifically so you can live-mess with coordinates while seeing the output immediately.
