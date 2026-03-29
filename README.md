# escher-laptop-loop

A lightweight browser-based Escher loop tool for the two-image workflow.

## Run locally on macOS

No build step required.

1. Clone/download this repo.
2. Open `escher.html` directly in your browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Workflow for your two provided images

1. Load the white-background version as **Image A**.
2. Load the black-background version as **Image B**.
3. Set **View = Loop A ↔ B**.
4. Optionally set **Render style = Original** to flip between your originals,
   or use red-line render modes with adjustable threshold/boost/blur.
5. Download either the current preview canvas, or processed A/B images.
