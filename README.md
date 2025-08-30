# Data Mining Project: Healthcare Spending, Inactivity, and Diabetes Mortality

## Overview
This project explores the relationships between **healthcare spending**, **physical inactivity**, and **diabetes-related mortality** across different countries. Using clustering techniques and visualization, the goal is to identify regional patterns and correlations that could provide insights into global health disparities.

## Project Structure
- **Datasets**
  - `Diabetes.csv` – Diabetes mortality statistics  
  - `Physical inactivity.csv` – Global physical inactivity rates  
  - `GHED_data.csv` – Healthcare expenditure data  
  - Preprocessed and merged files: `final.csv`, `final_with_clusters.csv`, etc.  
  - `ne_50m_admin_0_countries.shp` – Shapefile for geographic mapping  

- **Notebooks**
  - `preprocess.ipynb` – Data cleaning and preprocessing  
  - `analysis.ipynb` – Correlation analysis, clustering (K-Means), and visualization  

- **Outputs**
  - `world_map_by_cluster_high_res.png` – Visualization of country clusters  

## Methods
- Data cleaning and normalization of datasets  
- Correlation analysis between health indicators and healthcare spending  
- K-Means clustering (k=4, k=5, k=10) to group countries by health and economic factors  
- Geographic visualization of clusters  

## Requirements
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `geopandas`  

Install dependencies:
```bash
pip install -r requirements.txt
