# HGIS de las Indias – base maps

Territory base maps of [HGIS de las Indias](https://www.hgis-indias.net), one image per
territory and year (1701, 1725, 1750, 1775, 1787, 1800, 1808), served through GitHub Pages
for the ARCA encyclopedia.

- File name: `<WikiID>_<year>.webp`, e.g. `abancay_jurisdiccion_per_1750.webp`
  (WikiID as in the `entidades` table).
- `manifest.json` lists, per WikiID, the years that have a map.
- Converted from the original PNGs (WebP, quality 85) with
  `apps_as_factory/transform/compress_basemaps.py` in the repertorio-de-indias-flask repo.
