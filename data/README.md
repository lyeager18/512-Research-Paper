# Data documentation

Raw and cleaned data are **not committed** (see `.gitignore`). This file records where each source comes from. Update the "Downloaded" and "Version" columns as you go.

| Source | Where to get it | Access | Downloaded | Version |
|---|---|---|---|---|
| Asian Barometer Survey, Waves 3-5 | asianbarometer.org (online data application form) | Application required; redistribution restricted | Wave 3: 2026-11-11 | |
| ABS country technical reports | asianbarometer.org | Public | | |
| AidData GeoGCDF v3.0 | aiddata.org (GitHub repository linked from the data page) | Public | | 3.0 |
| AidData GCDF v3.0 (tabular) | aiddata.org | Public | | 3.0 |
| Administrative boundaries | GADM or geoBoundaries | Public | | |
| VIIRS nighttime lights | Earth Observation Group, Colorado School of Mines | Public | | |
| DMSP-OLS nighttime lights | NOAA | Public | | |

## Notes
- Asian Barometer: when applying, ask whether subnational identifiers are available under a restricted-use agreement.
- Match boundary vintage to survey years; administrative units have changed.
- Keep raw files untouched. Write cleaned versions to `data/clean/`.

## Sampling-unit log
One row per sampling unit with country, wave, province, district, commune, urban/rural, and geocoded coordinates. Do not commit it if it is derived from restricted data.
