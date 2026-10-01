# dawei_flood_landslide_gee_webapp

Google Earth Engine web app for Dawei District floods & landslides (30 Sep 2026).
Bilingual Myanmar/English. Credit: **MAGGA Initiative** | Geocode: **MIMU Pcodes v9.7**.

Main dashboard repo: https://github.com/tmyothu/flood-and-landslid-in-dawei

## Files
- `gee_app.js` — GEE Code Editor script (paste & Run, then Apps → Publish)
- `dawei_villages_points.geojson` — 64 village points, EPSG:4326 (upload as EE Table asset)
- `dawei_villages_table.csv` — same + Latitude/Longitude (alt asset upload)
- `township_summary.csv` / `.json` — per-township stats
- `aoi_bbox.json` — Dawei District AOI bbox (WGS84)
- `DATA_DICTIONARY.md` — field definitions
- `README_GEE.md` — full upload → run → publish guide

## Quick start
1. Code Earth Engine → Assets → New Table upload → `dawei_villages_points.geojson`
2. Set `ASSET_VILLAGES = 'users/YOU/dawei_villages_points'` in `gee_app.js`
3. Run → Apps → Publish new app → share URL (share asset publicly)
