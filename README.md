# remote sensing using landsat imagery analysis and prophet-based forecasting


## Overview
this project analyzes changes in lake surface water area from 1984–2025, 
detects anomalies (floods/spikes), and forecasts future trends using 
time-series models (Prophet)

## Features
- data cleaning (outlier removal, yearly aggregation)
- exploratory data analysis (boxplots, histograms, trends)
- forecasting with Prophet
- visualization of long-term patterns

## Results and Conclusion
the project successfully analyzed long-term changes in lake surface water area from 1984–2025 using Landsat-derived NDWI imagery. after cleaning and aggregating the data on a yearly basis, forecasting models were applied to predict future water area trends.

the model outputs align with real-world expectations: gradual decreases or fluctuations in water surface area, with anomalies corresponding to extreme events such as floods. this indicates that the forecasting approach is scientifically sound and provides valuable insight into hydrological dynamics.

in terms of accuracy metrics, the Mean Absolute Error (MAE ≈ 0.20) and Root Mean Square Error (RMSE ≈ 0.22) fall in the low-to-moderate range. these values are not unusually high for environmental time-series forecasting, and they are strongly influenced by occasional spikes in the dataset caused by floods and other anomalies. such rare extremes can inflate numerical error measures, even though the model continues to capture the broader seasonal and long-term trends effectively. such extreme values disproportionately affect numerical error metrics, even though the model is correctly capturing the broader seasonal and long-term patterns.

## This project

- provides a framework for integrating satellite imagery with time-series forecasting for other environmental applications.
- provides a data-driven framework for monitoring surface water bodies over time.
- demonstrates how remote sensing indices (ndwi) can be integrated with time-series forecasting models (prophet, decomposition techniques).
- offers a scalable workflow that can be applied to other regions, satellite datasets, or environmental variables (e.g., vegetation indices, urban expansion).
- supports hydrological and climate research, by quantifying surface water dynamics under natural variability and anthropogenic pressures.
- enables decision-making in water resource management and policy, especially for drought preparedness, flood risk assessment, and long-term conservation strategies.
