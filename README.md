# SAMOS2026-Core3CS-SALDANA-BAY
Capstone Group Assignment focusing on Saldana Bay
## Overview
This project forms part of the SAMOS Core 3 Climate Systems assignment.  
The objective is to analyse climatological ocean colour (chlorophyll) data together with bathymetry for a selected coastal region.

## Study Region
Saldanha Bay and the adjacent West Coast of South Africa, located within the Benguela Upwelling System.

## Data Sources

### 1. Bathymetry (GMRT)
- Global Multi-Resolution Topography dataset
- Provides seafloor elevation (m)
### 2. Chlorophyll (ESA-CCI Ocean Colour)
- Monthly climatological dataset
- Resolution: ~4 km
- Variable: chlorophyll concentration (mg m⁻³)

## Data Access

Due to file size limitations, datasets are **not included** in this repository.

Each user must download and place the following files inside:
```
`Capstone_Assesment/`
``

Required files:
- ESA-CCI chlorophyll dataset (.nc)
- GMRT bathymetry dataset (.grd)

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
