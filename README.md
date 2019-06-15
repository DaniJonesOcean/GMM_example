# Demonstration: Gaussian mixture modelling
This repository contains two small Argo float datasets, each containing about 1% of the total Southern Ocean profiles (up to early 2017). It also contains a Jupyter notebook that illustrates the application of GMM to the Argo temperature dataset. 

## Data description
There are two CSV files in this repository:
- Temperature profiles: Argo_T_profiles_very_small_subset.csv  [units °C]
- Salinity profiles: Argo_S_profiles_very_small_subset.csv  [practical salinity units, psu]

Each row represents a single Argo profile. The columns are variables associated with that profile, specifically:
- x : longitude (°E)
- y : latitude (°N)
- Temperature (°C) or salinity (psu) values at the indicated pressure levels (dbar)

Pressure is a commonly-used vertical coordinate for oceanographic data, in part because it can be directly measured by instruments while they are in the ocean. When reported in dbar, pressure values are somewhat close to depth values reported in metres. 

## Procedure
The demo procedure is described in the Jupyter notebook contained in this repository. See that file for further instructions.
