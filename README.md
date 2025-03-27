Air Quality EDA – AML Project

This repository contains exploratory data analysis (EDA) on the 2024 EPA county-level air quality dataset. The goal is to identify regions with poor air quality that may be linked to long-term health risks.

Files Included:
- air_quality_eda_hari_chandana.ipynb – Cleaned and visualized notebook
- annual_aqi_by_county_2024.csv – EPA AQI dataset (county level)
- annual_conc_by_monitor_2024.zip – Compressed concentration data (uploaded due to GitHub file size limits)

Key Tasks Performed:
- Data cleaning (handling missing values, outliers, duplicates)
- Label encoding of categorical variables
- Standard scaling of pollutant-related features
- Visualizations of PM2.5, PM10, Ozone, AQI levels, and hazardous days

Libraries Used:
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (LabelEncoder, StandardScaler)

Notes:
- Large dataset `annual_conc_by_monitor_2024.csv` is included as a ZIP file. 
- All analysis is performed in Python using Jupyter Notebook.
