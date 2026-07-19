# Curriculum Map — Interactive Reproduction

An interactive 3D reproduction of Marble's curriculum knowledge graph
(withmarble.com/curriculum), built on their open-source dataset.

- **1,590** micro-topics, colored by subject, positioned by age
- **3,221** prerequisite links drawn as threads
- Drag to spin · scroll to zoom · tap any dot to trace prerequisites

## Run it

Open `index.html` through a web server (not file://, because it fetches JSON):

```
python3 -m http.server 8000
# then open http://localhost:8000
```

Or deploy to GitHub Pages: Settings → Pages → Source: main / root.

## Files

- `index.html` — the app (self-contained; Three.js vendored in `vendor/`)
- `vendor/three.min.js` — Three.js r128 (no CDN dependency)
- `data/graph.json` — slimmed topics + dependencies for the viz

## Data & credit

Data © Marble, released as open data under **ODbL 1.0**.
Source dataset: https://github.com/withmarbleapp/os-taxonomy
The interactive front-end here is an independent reconstruction; Marble's
own site code is not open source.
