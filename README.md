📌 Project Overview

This project analyzes rainfall variability and spatial patterns in the Sonitpur district of Assam using statistical methods, machine learning, and geospatial analysis. The workflow integrates trend detection, clustering, predictive modeling, and satellite-based land classification to generate data-driven environmental insights. 



🎯 Objectives

Analyze annual and seasonal rainfall trends for Tezpur

Identify spatial rainfall patterns using spectral clustering

Predict rainfall using Random Forest regression

Generate Land Use/Land Cover (LULC) maps from satellite imagery

Estimate runoff and support water resource planning 



🧠 Key Technical Concepts

Machine Learning (Random Forest Regression)

Spectral Clustering (k-Nearest Neighbors graph)

Time-Series Trend Analysis (Mann-Kendall Test, Sen’s Slope)

Geospatial Analysis (DEM, Satellite Imagery)

Supervised Classification

Hydrological Modeling

⚙️ Methodology
📊 Data Collection

Rainfall data was collected from sources such as the National Centre for Environmental Information (NCEI) and NASA POWER Data Access Viewer and processed using Python. 


📈 Trend Analysis

Applied the Mann-Kendall test to detect statistically significant trends and used Sen’s Slope estimator to measure trend magnitude in hydro-meteorological time series. 



🧩 Spatial Clustering

Performed spectral clustering on rainfall data from 28 locations, forming three distinct clusters that reveal topography-driven rainfall variation. 



🤖 Machine Learning Model

Built a Random Forest regression model using precipitation and elevation as features.

Model Performance:

Training R² = 0.99, RMSE = 0.45 mm

Testing R² = 0.98, RMSE = 1.13 mm

These results indicate highly accurate rainfall predictions. 


🛰️ Geospatial Processing

Generated Digital Elevation Models to analyze terrain influences such as drainage patterns, slope, and flood-prone zones. 



🚀 Key Outcomes

✅ Identified statistically significant rainfall trends
✅ Detected spatial rainfall clusters across the district
✅ Developed a high-accuracy predictive model
✅ Produced geospatial datasets for environmental planning

🛠️ Tech Stack

Python

Scikit-learn

Pandas, NumPy

Matplotlib

QGIS / GIS tools

Remote Sensing Data

