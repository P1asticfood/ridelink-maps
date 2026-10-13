# RideLink maps

Offline map files for the RideLink app, published as releases. The app downloads a file once and checks its size and SHA-256 before using it, so files here must never be changed after release: a new map gets a new release and a new file name.

## Files

| Release | File | Size | SHA-256 |
|---|---|---|---|
| nepal-2026-10-12 | nepal-20261012.pmtiles | 85,407,266 bytes | 2c1d30ce252c0b89333f9dcbaaef85ad18995faba35e94319254c1f04394e3bf |

Each file is a PMTiles archive of vector tiles for a riding map: roads, tracks, water, town parks, glaciers, place names and boundaries, zoom 0 to 14. They are built from the [Protomaps](https://protomaps.com) basemap with the scripts in the RideLink app's `scripts/maps` folder.

## Licence

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/). Built from the Protomaps basemap.
