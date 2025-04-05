# SWAT_YB
# SWAT Model Inputs for Yerba Buena Watershed

This repository contains all the necessary input files and configuration settings for running the SWAT model in QGIS 3.16 specifically tailored for the Yerba Buena Watershed in Argentina. The provided inputs include raster data, climate and lookup files, and a shapefile containing the watershed outlet and modified parameters for accurate simulation.

## Contents

### Raster Files
- **Land Use Raster (`land_use.tif`):**  
  Provides the land cover classification data essential for determining hydrological responses.
- **Digital Elevation Model (DEM) (`dem.tif`):**  
  Contains topographic information used for watershed delineation and flow direction analysis.
- **Soil Type Raster (`soil_type.tif`):**  
  Offers soil classification data to help parameterize soil-water interactions.

### Files
- **Climate Files:**  
  Daily meteorological data files (e.g., precipitation, temperature, solar radiation) required by SWAT to drive the model.
- **Land Use Lookup File (`land_use_lookup.csv`):**  
  A mapping table that links land use classes from the raster with corresponding SWAT parameters.

### Shapefile
- **Watershed Outlet Shapefile (`watershed_outlet.shp` and associated files):**  
  Contains the geographic location of the watershed outlet along with customized parameters for running the model for the Yerba Buena Watershed.

## Directory Structure
Rasters: Land use, DEM, soil type
CSV files: weather, land use lookup table
shapefile: outlet
Parameters: list of parameters modified and values used


