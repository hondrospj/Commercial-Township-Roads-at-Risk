# Commercial Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Commercial Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01412150, Bivalve
- PETSS / NOAA station: 8536889
- NAVD88 thresholds: 4.19 ft minor, 5.19 ft moderate, 6.19 ft major
- MLLW thresholds: 7.6 ft minor, 8.6 ft moderate, 9.6 ft major
- MLLW = NAVD88 + 3.41 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Commercial Township boundary at 8.7-foot adaptive resolution.
