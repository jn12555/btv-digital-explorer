# Caleta Tortel model: data sources

- Building footprints, boardwalk and stair routes, piers, coastline, woods and bare rock: © OpenStreetMap contributors, Open Database Licence (ODbL), https://www.openstreetmap.org/copyright. Extract of 6 November 2026 in `src/osm.json`.
- Terrain: AWS Terrain Tiles (Terrarium encoding; sources include SRTM, GMTED2010 and ETOPO1; Mapzen), https://registry.opendata.aws/terrain-tiles/. Tiles of 6 November 2026 in `src/dem14.png` (zoom 14) and `src/dem11.png` (zoom 11).
- Building heights, colours, roofs, windows, stilts and trees are styled by tools/model3d/build_village3d.py (style: patagonian_timber); OpenStreetMap has no storey counts for the village.

Credit line for videos: "Map data © OpenStreetMap contributors · Terrain: AWS Terrain Tiles".
