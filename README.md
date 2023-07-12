# Zuber Rides Analysis

<p align="center">
  <img src="https://github.com/kellyshreeve/Zuber_Rides_Analysis/blob/main/images/carimage.png" 
  alt="Purple car cartoon">
</p>

# Project Overview

This repository hosts a data science project for Zuber, a new ride share company launching in Chicago. It is an in-depth analysis of customer behavior in the area and includes descriptive statistics, data visualizations, and hypothesis tests on data from competitors in the area.

# Installation and Setup

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

sql_result_01.csv
  * *company_name*: taxi company name
  * *trips_amount*: the number of rides for each taxi company on November 15-16, 2017  

sql_result_04.csv
  * *dropoff_location_name*: Chicago neighborhoods where rides ended
  * *average_trips*: the average number of rides that ended in each neighborhood in November 2017  

sql_result_07.csv
  * *start_ts*: picup date and time
  * *weather_conditions*: weather conditions at the moment the ride started
  * *duration_seconds*: ride duration in seconds

## Data Acquisition

The data were retrieved through HTML parsing a web page and SQL queries of a large database provided by TripleTen. Data were downloaded into csvs, and then uploaded into Python for analysis. 

## Data Preprocessing

Data were checked for missing values and duplicates. None were found and no imputation was necessary.
 
# Code Structure
```
  ├── LICENSE
  ├── README.md          
  ├── data
  │   ├── sql_result_01.csv      
  │   ├── sql_result_04.csv       
  │   └── sql_result_07.csv 
  │
  ├── images
  │   └── car-picture.png    
  │
  ├── notebooks  
  │   └── Zuber_Analysis.ipynb 
  │
  └── requirements.txt  
```

# Results and Evaluation

# Future Work

# Acknowledgments/References
