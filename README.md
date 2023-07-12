# Zuber Rides Analysis

# Project Overview

Zuber is a new ride share company launching in Chicago and would like to better understand customer behvior in the area. The analysis depicts the local market using data visualizations and tests whether there is a statistically significant difference in customer trip length during bad weather.

# Installation and Setup

To view the analysis, open Zuber_Analysis.ipynb

## Codes and Resources Used

  - <b>Editor Used</b>: Visual Studio Code
  - <b>Python Version</b>: 3.10.9

## Python Packages Used

  - <b>General Purpose</b>: NA
  - <b>Data Manipulation</b>: ```pandas```
  - <b>Data Visualization</b>: ```plotly.express```
  - <b>Statistical Analysis</b>: ```SciPy, researchpy```
  - <b>Machine Learning</b>: NA

## Installing development requirements

```pip install -r requirements.txt```

# Data

## Source Data

The analysis is based on three datasets: 
  1. Local ride share companies and their total number of trips (n=64)
  2. Local neighborhoods and their average number of drop offs (n=94)
  3. Ride share trips with start time, weather, and duration (n=1068)

## Data Acquisition

The data were retrieved through HTML parsing a web page and SQL queries of a large database provided by TripleTen. Data were downloaded into csvs, and then uploaded into Python for analysis. 

## Data Preprocessing

Data were checked for missing values and duplicates. None were found and no imputation was necessary.
 
# Code Structure
```
|--- data
|     |--- sql_result_01.csv
|     |--- sql_result_04.csv
|     |--- sql_result_07.csv
```

# Results and Evaluation

# Future Work

# Acknowledgments/References
