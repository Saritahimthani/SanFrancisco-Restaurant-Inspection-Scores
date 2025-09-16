# SanFrancisco-Restaurant-Inspection-Scores
lives, san francisco, environmental health, department of public health, dph, sfdph, restaurant scores, sanitary scores, inspections

# Inspection Data Analysis Project

This project analyzes inspection data to identify trends in violation descriptions, risk categories, and business locations. The analysis includes data cleaning, visualization, and mapping.

## Features
- **Data Cleaning**: Filters and ensures data integrity.
- **Visualizations**:
  - Top 10 Violations
  - Violations by Risk Category
  - Business Location Map
- **Interactive Map**: Uses `leaflet` to display inspection scores by location.

## Prerequisites
- R version 4.0 or higher
- Required libraries:
  - `tidyverse`
  - `lubridate`
  - `ggplot2`
  - `dplyr`
  - `tidyr`
  - `leaflet` (install if not present)

## Dataset
The script reads data from `ds.csv`. Ensure the dataset is located in the root directory.
