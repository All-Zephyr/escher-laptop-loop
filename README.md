# escher-laptop-loop

Easy website editor for your Mathematica-style Escher **single-image transform** script.

## Quick start (Mac)

1. Open `escher.html` directly in browser, or run:

```bash
python3 -m http.server 8080
```

2. Visit <http://localhost:8080>.
3. Upload your image and edit sliders live.

## Controls mapped to your Mathematica code

- **Center X / Center Y** -> `centerPx`
- **Zoom** -> `zoom`
- **Branch direction** -> `branchDir`
- **q parameter** -> `q` (used to compute `alpha = 1 - i log(q)/(2π)`)
- **Preview quality** -> speed vs detail (for faster live editing)

Click on the preview image to set center quickly.
Use **Download PNG** for full-quality output.

## Notes

- This tool produces one transformed still image (not a loop player).
- Top-right badge in the app shows the current version and the file's last edit timestamp.
