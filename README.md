# EV Market Segmentation

## Overview

This repository contains a comprehensive analysis of the Electric Vehicle (EV) market in India. The analysis includes data on the distribution of various types of vehicles across states, the growth of EV adoption over the years, and the number of EV manufacturers by state. Additionally, it features visualizations and forecasting to provide insights into market trends.

## Datasets

1. **State-wise EV Distribution Data in India**
   - **File**: `State wise data.csv`
   - **Description**: Contains information about the distribution of different types of vehicles and charging stations across various states in India.
   - **Columns**:
     - `S.no`
     - `State Name`
     - `Two Wheeler`
     - `Three Wheeler`
     - `Four Wheeler`
     - `Goods Vehicles`
     - `Public Service Vehicle`
     - `Special Category Vehicles`
     - `Ambulance/Hearses`
     - `Construction Equipment Vehicle`
     - `Other`
     - `total-charging-stations`
     - `Electric`
     - `Non-Electric`

2. **Yearly EV Growth Data in India**
   - **File**: `Year wise Growth of EV.csv`
   - **Description**: Provides data on the total number of EVs adopted each year.
   - **Columns**:
     - `Year`
     - `Total Count`

3. **State-wise EV Manufacturer Data in India**
   - **File**: `EV Maker by Place.csv`
   - **Description**: Lists the EV manufacturers and their locations across various states.
   - **Columns**:
     - `EV Maker`
     - `Place`
     - `State`

## Analysis

### 1. **Exploratory Data Analysis (EDA)**
   - **Data Loading**: Imports the datasets and displays basic information.
   - **Data Inspection**: Checks the structure and types of the data.

### 2. **Visualizations**
   - **State-wise Distribution of Vehicles**: Stacked bar chart showing the distribution of different types of vehicles by state.
   - **Total Count of Each Vehicle Type**: Bar graph displaying the total count for each vehicle type.
   - **Distribution of Each Vehicle Type by State**: Bar plots for different vehicle types across states.
   - **Analysis of Charging Infrastructure**: Bar chart showing the distribution of charging stations by state.
   - **Distribution of Electric vs. Non-Electric Vehicles**: Pie chart illustrating the proportion of electric and non-electric vehicles.
   - **Yearly Trends in EV Adoption**: Line plot showing the growth of EV adoption over the years.
   - **Number of EV Manufacturers by State**: Bar chart depicting the number of EV manufacturers by state.

### 3. **Forecasting**
   - **ARIMA Model**: Forecasts future EV adoption trends based on historical data.
   - **Visualization**: Line plot comparing historical data and forecasted values.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`

You can install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn statsmodels

