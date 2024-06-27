# Formula 1 Data Analysis

![Alt Text](https://github.com/luigiascio/Thesis-Behind-the-Performances-of-Formula-1/blob/main/Immagine1.png)

This repository contains the code and data analysis for a thesis focused on leveraging Python to analyze Formula 1 data. The analysis demonstrates how data from past races can be processed to extract valuable insights about performance, strategy, and race dynamics.

## Project Overview

The main objective of this project is to show how Python can be used to analyze historical motorsport data, particularly from Formula 1 races, and to extract useful information. The analysis includes:

- Data collection and transformation
- Simple statistics and correlation analysis
- Linear regression modeling
- Telemetry comparison
- Performance analysis of teams over different tire compounds

## Data Collection

The data used in this project includes all laps of all drivers in the Formula 1 championships from 2019 to 2023. This period was chosen due to significant changes in tire regulations introduced in 2019.

## Libraries and Tools

The analysis is performed using the following libraries:

- **FastF1**: For accessing and processing Formula 1 data including session results, telemetry, and track conditions.
- **Pandas**: For data manipulation and creation of dataframes.
- **Numpy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For building and evaluating regression models.
- **Statsmodels**: For statistical modeling.

## Analysis Structure

1. **Data Collection and Transformation**:
    - Extraction of race data using FastF1.
    - Filtering laps based on criteria such as lap time and validity.
    - Creation of dataframes for further analysis.

2. **Descriptive Analysis**:
    - Calculation of simple statistics for variables such as lap time and top speed.
    - Visualization of data distribution across different teams and drivers.

3. **Correlation and Regression Analysis**:
    - Performance of correlation analysis between variables.
    - Estimation of linear regression models to understand performance trends.

4. **Telemetry Comparison**:
    - Detailed comparison of telemetry data for the fastest laps and between different drivers.

5. **Performance Analysis Over Years**:
    - Analysis of team performances over the years considering different tire compounds.
    - Normalization of data and study of the correlation with external variables such as temperature.

## Key Findings

- The analysis highlights significant insights such as the performance variations between drivers and teams, the impact of tire compounds on race strategy, and the correlation of performance with external factors.
- The regression models provide a clear picture of performance trends over the race.

## Conclusion

This project demonstrates the power of data analysis in understanding and improving performance in Formula 1. The use of Python and specialized libraries like FastF1 enables detailed and insightful analysis of vast amounts of motorsport data.
