# Interactive 3D House Viewer

Single file: `house-3d.html` (Three.js loads from a free CDN, so an internet connection is needed).

## Open it
- **Phone or PC:** open `house-3d.html` in Chrome, Edge, Firefox or Safari.
- **Controls:** one finger rotates, two fingers pinch to zoom and drag to pan. Mouse: left drag rotates, wheel zooms, right drag pans.
- **Buttons:** 3D VIEW, TOP VIEW, ROOF ON/OFF, ROOM LABELS, DIMENSIONS, RESET CAMERA. Tap **VERIFY ⓘ** for open questions.

## Share it with a public URL (all free)
1. **Netlify Drop (easiest):** rename the file to `index.html`, put it in a folder, drag the folder onto app.netlify.com/drop. You get a public link instantly.
2. **GitHub Pages:** create a public repo, upload `index.html`, then Settings → Pages → Deploy from branch `main` / root. URL: `https://<username>.github.io/<repo>/`.
3. **Vercel:** import the repo (or drag the folder) at vercel.com/new.

## Accuracy notes (VERIFY)
- Stated sizes don't add up: the south row (5 + 5 + 11 + 11'6" + 12 ft = 44.5 ft) exceeds the 37'-6" plot width. The drawing isn't to scale, so geometry is traced from its proportions (about 26 px per ft). Labels show the sizes written on the plan.
- Main entrance door is not drawn on the plan.
- Assumed: 9 in walls, 10 ft ceiling, window sizes, staircase step count. Furniture is illustrative.
- To change anything, edit the `W` (walls), `O` (doors/windows) and `R` (rooms) arrays near the top of the script.
