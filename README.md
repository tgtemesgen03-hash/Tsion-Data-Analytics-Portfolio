NYC Airbnb Analysis Project
Project Overview
This project explores New York City's Airbnb market using 2019 listings data. The goal is to understand pricing patterns, neighborhood trends, and factors that influence listing prices. Insights can help hosts optimize pricing and listings, and travelers make informed decisions.

The analysis includes:
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Neighborhood and borough comparisons
Geographic visualizations (maps and heatmaps)
Predictive modeling of listing prices
Feature importance analysis
Interactive dashboards and word cloud visualizations

Folder Structure:
project_folder/
 data/ AB_NYC_2019.csv # Full dataset (from Kaggle)
 NTA.geo.json.txt # For Choropleth Neighborhood Map
 boroughs.geojson.txt # For Choropleth Borough Level Map

notebooks/
 Final Project DATS 2102.ipynb # Jupyter Notebook with narrative and figures

output/
 nyc_prices_map.html
 nyc_airbnb_nta_median_price_map.html
 nyc_airbnb_median_price_map.html 

quarto-rendered html/
 Final Project DATS 2102.html # Quarto rendered HTML version

slides/
 NYC_Airbnb_Presentation.pptx # Slide deck for presentation

recordings/
 demo_recording.m4a # 1–3 minute demo video/audio

docs/
 data_dictionary.ipynb # Data dictionary and schema

read_me.mb # This file


Data Access:
Primary Source:
New York City Airbnb Open Data (Kaggle)
File: AB_NYC_2019.csv (contains ~48,000 listings)
Example:
import pandas as pd
df = pd.read_csv("C://Users//Tsion T//Downloads//project_folder//data//AB_NYC_2019.csv")

Dependencies:
Python 3.9+
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Folium
Scikit-learn
WordCloud

How to Run:
Open the notebook: project_folder/notebooks/Final Project DATS 2102.ipynb
Run all cells sequentially (data cleaning, EDA, maps, modeling, dashboards).

Notes / Tips:
Use relative paths (../data/...) to ensure portability.
Full dataset is large; use the synthetic sample for quick testing.
Interactive dashboards and Folium maps require Jupyter Notebook or JupyterLab.

Contact / Author:
Name: Tsion Temesgen
Email: tgtemesgen03@gwu.edu
Course / Project: NYC Airbnb Analysis, Data Visualization


This README includes:
Project overview
Folder structure
Data access instructions
Data dictionary
Dependencies and install instructions
Run instructions and tips
Data Sources



Data Sources::
New York City Airbnb Open Data (2019)
Source: Inside Airbnb / Kaggle
URL: https://services5.arcgis.com/GfwWNkhOj9bNBqoJ/arcgis/rest/services/NYC_Borough_Boundary/FeatureServer/0
Accessed: December 2025
Description: Contains detailed Airbnb listing information for NYC, including prices, locations, room types, availability, and neighborhood data.

NYC Neighborhood Tabulation Areas (NTA) GeoJSON
Source: NYC Open Data
URL: https://github.com/nycehs/NYC_geography/blob/master/NTA.geo.json
Accessed: December 2025
Used for choropleth mapping at the neighborhood level.

NYC Borough Boundaries GeoJSON
Source: NYC Open Data
URL: https://www.arcgis.com/home/item.html?id=1f75b59e45444d7bae27454ec7730395&sublayer=0
Accessed: December 2025
Used for borough-level geographic visualizations.

