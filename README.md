# GIST 604B – Python for GIS

Repository for working with tabular, vector, and raster GIS data using Python.

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   ├── Dockerfile
    ├── data/
    │   ├── neighborhood_samples.geojson
    │   ├── temperature_readings.csv
    │   ├── weather_stations.csv
    │   ├── cities/
    │   │   └── ne_cities_us.geojson
    │   ├── ecoregions/
    │   │   └── epa_level3_western_us.geojson
    │   └── protected_areas/
    │   │   └── national_parks_major.geojson
    ├── notebooks/
    │   ├── pandas/
    │   ├── geopandas/
    │   └── rasterio/
    ├── src/
    │   ├── pandas_basics.py
    │   ├── geopandas_basics.py
    │   └── download_real_data.py
    ├── tests/
    │   ├── test_pandas_basics.py
    │   └── test_geopandas_basics.py
    ├── pyproject.toml
    └── uv.lock

## Notes

- Notebooks are for exploration and learning.
- Final implementations are in `src/`.
- Tests validate pandas and GeoPandas functionality.
- Rasterio work is completed entirely in the notebook.