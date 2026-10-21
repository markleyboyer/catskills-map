# Explore the Catskills: web map

An interactive version of the Catskills Visitor Center's *Explore the Catskills* map, built with [MapLibre GL JS](https://maplibre.org) and [PMTiles](https://protomaps.com/docs/pmtiles).

Live at https://markleyboyer.github.io/catskills-map/

- `index.html`: the whole page: map style, layer key and pop-ups
- `tiles/overlays.pmtiles`: vector tiles for trails, places, land, water, roads and byways
- `fonts/`: label glyphs (Noto Sans)

The tiles are generated from GIS source data by a separate build pipeline that isn't part of this repository.

**Data:** NYS DEC, NYC DEP, USGS NHD, © OpenStreetMap contributors. **Background:** © Mapbox, © Maxar.
**Cartography:** Markley Boyer, after the 2024 print map by Partner & Partners.
