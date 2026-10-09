# ECLAC Capstone

Scripts to download indicators from the ECLAC CEPALSTAT open-data API.

## Data
- Household indicator CSVs: `Databases/`
- Full database (all indicators, SQLite, ~2 GB uncompressed, 214 MB compressed):
  download `cepalstat_all.db.gz` from the
  [Releases tab](https://github.com/Phirtia/ECLAC_Capstone/releases/tag/v1.0),
  then run `gunzip cepalstat_all.db.gz`.

Source: ECLAC, CEPALSTAT.

## Regenerate the data
Run `Scripts/eclac_api.ipynb`.
