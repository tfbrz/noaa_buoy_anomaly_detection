## NOAA Buoy Anomaly Detection
Time Series Anomaly Detection on NOAA Buoy Sensor Data

## Project Overview
This project analyzes environmental sensor data collected from an Oregon-based NOAA (National Oceanic and Atmospheric Administration) buoy station to detect anomalous ocean and atmospheric events. Time-series modeling and unsupervised machine learning techniques are applied to identify unusual patterns in wind speed, wave height, pressure, and temperature data.

## Methods
- SARIMA residual modeling
- DBSCAN clustering
- Isolation Forest
- Time-series feature engineering

## Characteristic Anomaly Patterns

The figure below shows average standardized sensor behavior within ±12 hours of detected anomalies. Three recurring environmental signatures emerge:

- **Winter Storm:** decreasing pressure with increasing wind speed and wave height  
- **Remote Swell:** elevated wave heights while atmospheric variables remain stable  
- **Local Wind Burst:** wind-driven wave increases without significant pressure changes  

![Anomaly Pattern Signatures](noaa-buoy-anomaly-detection/images/final_plots/mean_categ_anom.png)
