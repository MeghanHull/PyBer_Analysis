# PyBer Analysis
## Overview of Analysis
<!-- V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer. -->
### Project Background


### Purpose
The purpose of this analysis is to summarize and visualize ride-sharing data by city type, in order to assess how those differences can be used by decision-makers at PyBer.

### Resources
Data Sources:
1. [city_data.csv](Resources/city_data.csv)
2. [ride_data.csv](Resources/ride_data.csv) 

Software: Python 3.7

Analysis Code: [PyBer_Challenge.ipynb](PyBer_Challenge.ipynb)

## Results
<!-- Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. -->
### Summary by City Type
Data has been summarized by rural, suburban, and urban population sizes. From the table below, it is evident that:
- There are more rides and more drivers as population increases.
- The average fare per ride and per driver decreases as population increases.

|          | Total Rides   | Total Drivers   | Total Fares   | Average Fare per Ride   | Average Fare per Driver   |
|:---------|:-------------:|:---------------:|--------------:|:-----------------------:|:-------------------------:|
| Rural    | 125           | 78              | $4,327.93     | $34.62                  | $55.49                    |
| Suburban | 625           | 490             | $19,356.33    | $30.97                  | $39.50                    |
| Urban    | 1,625         | 2,405           | $39,854.38    | $24.53                  | $16.57                    |

<sup><sub>Source: Table generated with [PyBer_Challenge.ipynb](PyBer_Challenge.ipynb), using the data sources in [Resources](#resources) </sub></sup>

Analyzing the weekly fare data in the chart below, totals by city type appear fairly consistent, within a $500 USD spread.  

![PyBer_fare_summary.png](analysis/PyBer_fare_summary.png)

<sup><sub>Source: Chart generated with [PyBer_Challenge.ipynb](PyBer_Challenge.ipynb), using the data sources in [Resources](#resources) </sub></sup>

## Summary
<!-- Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types. -->
