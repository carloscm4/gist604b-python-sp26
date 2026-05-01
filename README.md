# Python GIS Analysis

**Student:** Carlos Castillo    
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 3 – Python GIS  
**University of Arizona**

---

## Project Description
This project demonstrates the use of Python for geospatial data analysis. It includes working with tabular, vector, and raster datasets using libraries such as pandas, GeoPandas, and Rasterio.

---

## Tools and Technologies
- Python
- pandas
- GeoPandas
- Rasterio
- Jupyter Notebooks
- GitHub Codespaces

---

## What I Did
- Loaded and explored GIS datasets using pandas  
- Filtered and summarized environmental data  
- Performed spatial analysis using GeoPandas  
- Conducted raster analysis including NDVI calculations  

---

## How to View / Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the project in VS Code or GitHub Codespaces  
3. Navigate to the `notebooks/` folder  
4. Run the notebooks step-by-step  

---

## Repository Structure
```
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
```
