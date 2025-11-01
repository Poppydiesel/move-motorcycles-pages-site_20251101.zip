
# Move Motorcycles — GitHub Pages Site

This folder is ready to be pushed to a GitHub repository and served via **GitHub Pages**.

## Files
- `index.html` — your master interactive map.
- `.nojekyll` — disables Jekyll so asset paths work as-is.
- `data/` — place any future GeoJSON (e.g., exported marker positions) here.
- `404.html` — (optional) basic 404 that links back to the map.

## How to deploy
1. Create a new public repository on GitHub (e.g., `move-motorcycles-map`).
2. Upload the contents of this folder (or commit/push via git).
3. In **Settings → Pages**, set:
   - **Build and deployment**: *Deploy from a branch*
   - **Branch**: `main` (or `master`) and folder `/ (root)`
4. Click **Save**. Within a minute or two, your site will be live at:
   - `https://<your-username>.github.io/<your-repo>/`

## Embedding in Wix
Use a standard HTML iframe element and point the `src` to your Pages URL above.

## Notes
- Markers are **32×32** with **14px** numbers, draggable.
- Use the **Export Numbers (GeoJSON)** button to snapshot positions.
- Your dataset/lines remain visible; the toggle only hides/shows labels.
