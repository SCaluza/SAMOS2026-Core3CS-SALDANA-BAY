# SAMOS2026-Core3CS-SALDANA-BAY
Capstone Group Assignment focusing on Saldana Bay
## Overview
This project forms part of the SAMOS Core 3 Climate Systems assignment.  
The objective is to analyse climatological ocean colour (chlorophyll) data together with bathymetry for a selected coastal region.

## Study Region
Saldanha Bay and the adjacent West Coast of South Africa, located within the Benguela Upwelling System.

## Data Sources
## 1. Bathymetry (GMRT)
- Global Multi-Resolution Topography dataset
- Provides seafloor elevation (m)
## 2. Chlorophyll (ESA-CCI Ocean Colour)
- Monthly climatological dataset
- Resolution: 4 km
- Variable: chlorophyll concentration (mg m⁻³)

## Methodology 
The analysis was conducted in JupyterLab.
The following steps were performed:
- Bathymetry and chlorophyll datasets were loaded using xarray
- Study region was subset from global dataset
  # Bathymetry Mapping
- Bathymetry map was generated to visualise seafloor depth
  # Annual Mean Chlorophyll Map
- The annual mean chlorophyll-a concentration map was produced to show overall productivity patterns in the region
  # Monthly Chlorophyll-a Maps
- A faceted figure consisting of 12 subplots was created, each subplot represents the spatial distribution of chlorophyll-a for a specific month
  # Time Series Analysis
- Time series were computed for:regional mean and selected high productivity grid point

## Figures 
 # 1. Bathymetry map
 - A bathymetric map was generated to illustrate the seafloor depth across the study region.
 - This supports the interpretation of circulation patterns and potential upwelling regions.
 # 2. Annual mean chlorophyll-a concentration
 - An annual mean chlorophyll-a map was produced to show the overall spatial distribution of phytoplankton biomass.
 # 3. Monthly chlorophyll-a maps
 - A faceted figure was created to display the spatial distribution of chlorophyll-a concentration across the study region for each month of the year.
 -  The figure consists of 12 subplots arranged in a 3 × 4 grid, with each panel representing the monthly climatological mean of chlorophyll-a
# 4. Time series
 -A time series plot was generated to compare the mean seasonal cycle of chlorophyll-a across the study region with values from a single grid point located in a high-productivity area.
- This comparison highlights differences between overall regional trends and localised variability.

## Data Access
Due to file size limitations, datasets are not included in this repository. 
Each user must download and place the following files inside:
```
`Capstone_Assesment/`
``
Required files:
- ESA-CCI chlorophyll dataset (.nc)
- GMRT bathymetry dataset (.grd)

# How to Run the Project
- Clone the repository
- Open JupyterLab
- Navigate to the project folder
- Run the notebook cells sequentially

# Dependencies 
- xarray
- matplotlib
- cartopy
- pandas
- cmocean
- numpy


## Notebook

The main analysis is contained in:

ocean_colour_analysis.ipynb

The notebook includes:
- Bathymetry visualisation
- Chlorophyll climatology analysis
- Seasonal variability (monthly maps)
- Time series comparison

## Figures
Figures generated in the analysis are stored in:

figures/

## Notes

- Data paths are defined relative to the repository for reproducibility.
- Large datasets are excluded using `.gitignore`.
- Each group member must download the required datasets locally and place them in the specified folder structure.
This repository is structured to ensure reproducible scientific analysis across different systems.
``
