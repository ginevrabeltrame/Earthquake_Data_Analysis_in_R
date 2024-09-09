# Earthquake Data Analysis (1921-2021)

## Overview
This project focuses on the analysis of earthquake data spanning from 1921 to 2021. The analysis was conducted as part of the _Advanced Statistics_ course and aims to explore various statistical properties of seismic events using R.
The dataset includes earthquake magnitudes, depths, locations, and time intervals. The project applies several statistical techniques, such as clustering, time series analysis, and visualization, 
to gain insights into seismic activity over the past century.

## Features
- **Seismic Activity Visualization**: Heatmaps, contour plots, and density maps to display earthquake distribution.
- **Clustering Analysis**: K-means clustering to identify patterns in earthquake locations and magnitudes.
- **Time Series Forecasting**: ARIMA and VAR models applied to analyze temporal trends in seismic activity.
- **Power Law Distribution Fit**: Investigating the magnitude distribution following a power law.

## Key Packages
The project primarily uses the following R packages:
- `ggplot2`: For visualization of seismic data.
- `dplyr`: For data manipulation and transformation.
- `cluster`: For K-means clustering analysis.
- `forecast`: For time series forecasting using ARIMA models.
- `magick`: To create GIFs illustrating the evolution of clustering over time.

The complete package list can be found in the jupyter notebook.

## How to Run
1. Clone the repository:
    ```bash
    https://github.com/ginevrabeltrame/Earthquake_Data_Analysis_in_R
    ```
2. Install the necessary R packages:
    ```R
    install.packages(c("ggplot2", "dplyr", "cluster", "forecast", "magick"))
    ```
3. Load the dataset and run the analysis in the provided R scripts.

## Results
The project provides an in-depth exploration of seismic patterns, including:
- **Seismic Density**: Identifying regions with the highest seismic activity in Italy and other locations.
- **Cluster Analysis**: Grouping seismic events by magnitude and location.
- **ARIMA Residuals**: Checking the autocorrelation and distribution of residuals to ensure optimal model fit.


