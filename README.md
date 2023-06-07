# Weather Data Analysis
This repository contains Python code for analysing a dataset of weather measurements.

## Description
The data includes daily weather measurements such as temperature, humidity, dew point, barometric pressure, wind speed, gust speed, and precipitation. The analysis includes:

- Calculating standard deviations of various measurements
- Determining the 50th and 75th percentile of average temperature
- Calculating the Pearson correlation between average dew point and average temperature
- Finding the month with the lowest average humidity
- Determining the month with the highest median for maximum gust speed
- Calculating the average temperature between certain date ranges
- Determining the range of average temperature for a specific month
- Finding the day with the highest difference between maximum and minimum pressure
- Counting the number of days with a barometer reading equal to the median of all readings
- Counting the number of days where the average temperature is within one standard deviation of the mean average temperature

## Installation
To run this project, you will need to install the following Python packages:

`pip install pandas numpy scipy`

## Usage
Clone the repository to your local machine.
Load your data into a pandas DataFrame.
Run the Python script to analyze your weather data.
