# Norway National Parks — Interactive GeoJSON Map

This folder is ready to deploy. It renders `data/national_parks.geojson` over `data/basemap.geojson`
with D3, and supports click-to-highlight (green) + bold labels, plus light zoom.

## Run locally
```
python -m http.server 8080
# open http://localhost:8080/
```

## Deploy (GitHub Pages)
- Push the contents of this folder to your repo (at the root).
- In the repo: Settings → Pages → Deploy from branch → (your default branch) → root → Save.

## Notes
- Detected park name field: **navn**
- If labels look odd, tweak the `getName()` helper in `index.html`.
