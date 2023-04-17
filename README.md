# labrador-sea-oxygen

This repository contains code used for a paper submitted to Frontiers in Marine Science on April 7, 2023, titled "Decadal variability of oxygen uptake, export, and storage in the Labrador Sea from observations and CMIP6 models". The notebooks included in the repository show examples of the calculation of a "model score", which assesses the ability of models to reproduces observed oxygen data. There are currently two notebooks showing examples of the score calculation:
* [cmip6_score](./cmip6_score.ipynb), which uses OpenDAP URLs to directly access files from the server for the **MIROC E2SL** and **NOAA GFDL CM4** models
* [cmip6_score_local](./cmip6_score.ipynb), which includes data for more models \(three as of Apr 17, 2023\), but requires the CMIP6 data to be downloaded separately to run the notebook


#### April 17, 2023
Added second notebook to have separate examples for online calculation of scores

#### April 14, 2023
Added code for the calculation of the model score. Current version includes examples for CMIP6 gridded model data from MIROC E2SL, NCAR CESM2 and NOAA GFDL. Note that the CMIP data are currently not uploaded on GitHub, so to run the code the user would have to separately download the data.
