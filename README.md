# B/SPOKE website prototype

Static prototype of the redesigned bspokestudios.com home page. It is a design proposal by Amalgama and is still in review with B/SPOKE.

## Run locally

The page uses root-relative paths (`/assets/...`), so serve the folder instead of opening the file directly:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

On Vercel it deploys as a static site with no build step.

## Structure

- `index.html`: the whole home page, with markup, styles and the small script that renders the sections and runs the scroll animations.
- `assets/`: photos, videos and the studios map.

## Notes

- Fonts load from Google Fonts. Figtree stands in for Visuelt Pro, which still needs a web license.
- The studios map uses Esri and OpenStreetMap tiles. The map provider for production is still to be defined.
- Images and videos are B/SPOKE's current site material.
- Not final copy or images:
  - the app phone screens and the Recovery image are stand-ins;
  - some copy changes are still waiting for B/SPOKE's approval.
