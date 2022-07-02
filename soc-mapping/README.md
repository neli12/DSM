## Mapping Soil Organic Carbon

Hey there!

In this repository I am presenting a simple example to estimate soil organic carbon (SOC) spatially. I used a Sentinel-2 median surface reflectance image (median of 3 years, 2018-2021) and calculated some spectral indices. The spectral bands and spectral indices were used as predictors in a Random Forest model. Unfortunately, the dataset is private and cannot be shared but this is just an example to represent a way to estimate SOC content and can be applied with other datasets.  
Is worth mentioning that this is a very simple example and here I am not considering hyperparameterization and multicollinearity (which is high between spectral bands and indices), tasks that must be considered to improve ML models.  

I hope you enjoy learning about this!
