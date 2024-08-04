# Weather Data Analysis Project
This repository contains a Jupyter Notebook and SQL script for analyzing weather data.

## Files/contents

- `weather_data_analysis.sql`: SQL queries for analyzing the weather dataset.
- `weather_dataset.ipynb`: Jupyter notebook containing Python analysis of the weather data.
- `1. Weather Data.csv`: the raw weather data

## Data Description

The dataset contains the following columns:
- Date/Time
- Temperature (°C)
- Dew Point Temperature (°C)
- Relative Humidity (%)
- Wind Speed (km/h)
- Visibility (km)
- Pressure (kPa)
- Weather

## Analysis Performed

1. Basic statistical analysis of weather parameters
2. Correlation between different weather variables
3. Frequency of various weather conditions

## SQL Queries

The SQL script includes queries to:
1. Find clear weather records
2. Count instances of specific wind speeds
3. Check for NULL values
4. Rename columns
5. Calculate mean visibility
6. Find records with specific wind speed and visibility
7. Calculate mean values for each weather condition
8. Find instances of clear weather with specific humidity or visibility
9. Count snow-related weather conditions

## Python Analysis
The Jupyter Notebook includes Python code to perform the following analyses:

1. Find all records where the weather was exactly clear
   - Filters the dataset to show only clear weather conditions

2. Count instances of specific wind speeds
   - Determines how many times the wind speed was exactly 4 km/hr

3. Check for NULL values
   - Examines the dataset for any missing or null values across all columns

4. Rename columns
   - Demonstrates how to rename the "Weather" column to "Weather_Condition"

5. Calculate mean visibility
   - Computes the average visibility across the entire dataset

6. Find records with specific wind speed and visibility
   - Identifies records where wind speed is greater than 24 km/hr and visibility is equal to 25 km

7. Calculate mean values for each weather condition
   - Groups the data by weather condition and calculates the mean of each numeric column

8. Find instances of clear weather with specific humidity or visibility
   - Locates records where the weather is clear and relative humidity is greater than 50%, or visibility is above 40 km

9. Count snow-related weather conditions
   - Determines the number of weather conditions that include snow

## Usage

1. Run the SQL queries in your preferred SQL environment (e.g., DBeaver).
2. Open the Jupyter notebook in Jupyter Lab or Jupyter Notebook to run the Python analysis.

# weather_data_analysis
