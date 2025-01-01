# Berlin’s Environmental Dynamics: A Multi-Dimensional Analysis of Temperature, Vegetation, and Urban Development
## Overview
This repository contains code and resources for analyzing Land Surface Temperature (LST) patterns using Google Earth Engine (GEE). The project focuses on understanding the relationship between urban land use/land cover changes and their impacts on surface temperature variations.
Features

## Retrieval of LST from Landsat satellite imagery
- Calculation of various spectral indices (NDVI, NDBI, NDWI)
- Analysis of temporal LST changes
- Correlation analysis between LST and land cover types
- Visualization of LST patterns and thermal variations

## Prerequisites

- Google Earth Engine account
- Basic understanding of remote sensing concepts
- Familiarity with JavaScript (for GEE Code Editor)

## Tools & Libraries
### Required

- Google Earth Engine JavaScript API
- Earth Engine Python API (optional)
- QGIS for visualization (3.x+)
- Jupyter Notebook

### Python Libraries

- geopandas
- numpy
- pandas
- matplotlib
- scipy
- contextily
- seaborn

### JavaScript Libraries

- ee (Earth Engine JavaScript API)
- Chart libraries for visualization
- Export utilities

## Data Sources

- Landsat 8 OLI/TIRS imagery
- Landsat 5 TM imagery (for historical analysis)
- Land use/land cover data
- Administrative boundaries
- Baumkataster - Berlin

## Methods
The repository implements various approaches for LST analysis:

- Radiative transfer equation method for LST retrieval
- Land use/land cover classification
- Statistical correlation analysis
- Temporal trend analysis
