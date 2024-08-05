# Remote Sensing Course Final Project

Welcome to the repository for my final project in the Remote Sensing course. This repository contains the code and the necessary data for the project.

## Project Overview

This project aims to calculate the evapotranspiration of a specific 50km x 50km polygon in northern Israel. This involves using data from multiple sources and applying the energy balance equation to calculate latent heat, which is then converted to evapotranspiration.

## Data Sources

The project utilizes data from:
- Google Earth Engine
- WRF files
- LSA SAF

The data includes variables such as emissivity, albedo, soil temperature, land cover type, LAI, temperature at 2 meters height, and wind speed.

## Dependencies

The project uses the following Python libraries:
- NumPy
- Pandas
- rioxarray
- Rasterio
- Shapely
- Cartopy
- Geopandas
- PyCRS

## How to Run the Code

1. Ensure the data directory is stored in your Google Drive at MyDrive/.
2. Replace the GEE authentication username with your own.
3. Run the Jupyter Notebook file.

## Contact

Feel free to explore the repository, and don't hesitate to contact me if you have any questions or suggestions.

Enjoy!
