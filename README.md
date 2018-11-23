# SoilMoisture
Soil moisture model
1D layered model to invert for subsurface soil moisture based on superficial SMOS SM data (passive remote sensing)

Objective: create a layered subsurface soil moisture model until about 2 – 3 m depth from surface SM data only

Steps A: Calibration and comparison of TREMP soil moisture profile and SMOS data

1) create 3D grid of soil moisture measurements of the area TREMP (close to BCN)

2) determine soil horizons according to soil moisture and spatial and temporal soil moisture variability;
important parameters: vegetation (upper layer), soil texture, topography (including former weathering processes)

3) define boundary conditions: subsurface flux (meteorogical observations: (evapotranspiration, percipitation, temperature), vegetation, percolation depending on soil texture …), constant flux on the very bottom of the model, ‘interfluxes’ between horizons

4) Using REMEDHUS or CEMADEN datasets for validation: Is it possible to invert from SMOS SM data to obtain soil moisture profile of REMEDHUS?

Nice to think about once obtained a subsurface model from SMOS SM data only: 

Predict the soil moisture content from the created subsurface model based on superficial SMOS SM data and climate data 

or 

predict future SMOS SM data from the observed model and climate data 

I) things to keep in mind:

differences in resolution of SMOS and TREMP

coupled model: climate model + created model from SMOS SM data
