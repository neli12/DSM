<img src = "https://img.shields.io/github/last-commit/neli12/DSM-clay-content"> <img src = "https://img.shields.io/github/languages/count/neli12/DSM-clay-content"> <img src = "https://img.shields.io/github/license/neli12/DSM-clay-content?color=green"> <img src = "https://img.shields.io/github/downloads/neli12/DSM-clay-content/total"> <img src = "https://img.shields.io/github/watchers/neli12/DSM-clay-content?style=social">

# Digital mapping of soil clay content
(work in progress!)  

Hey there! In this tutorial I want to show and explain how to spatially estimate the distribution of clay content across an area in Python, using jupyter notebook and some packages such as geopandas and shap. Because the geopandas package is difficult to install, I created a new environment in the conda prompt and installed there the geopandas, following the instructions given in this [link](https://medium.com/analytics-vidhya/fastest-way-to-install-geopandas-in-jupyter-notebook-on-windows-8f734e11fa2b). 

## Datasets

The follwing datasets were used: 

- `dataset.csv`: This file contains four columns
    - `X` and `Y`: Longitude and Latitude coordinates in EPSG: 4326 (WGS84).
    - `Clay.gkg`: Clay content in the soil in grams per kilogram.
    - `OM.gkg`: Organic matter content in the soil in grams per kilogram.
- `SYSI.tif`: Bare soil image with six spectral bands used as predictors of the behavior of the clay content in the modeling process.
