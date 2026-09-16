# Electric Vehicle Cars – Comprehensive Analysis

## Project Overview

This project focuses on analysing Electric Vehicle (EV) data to understand the relationship between EV specifications, driving conditions, and real-world driving range.

The project uses Python for data cleaning, preprocessing, analysis and visualization, and Power BI for creating interactive dashboards.

## Objective

The main objective is to identify important factors associated with real-world EV driving range and understand how different EV specifications and driving conditions influence performance.

## Dataset

**Dataset:** India EV Range Dataset  
**Source:** Hugging Face  
**Original Dataset:** 7,291 rows and 25 features  
**Project Dataset:** 800 rows and 12 original columns

### Main Features

- Make
- Model
- Variant
- Battery Capacity (kWh)
- Motor Power (kW)
- Vehicle Weight (kg)
- Motor Efficiency (%)
- ARAI Certified Range (km)
- Average Driving Speed (km/h)
- Ambient Temperature (°C)
- Traffic Condition
- Real World Range (km)

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Power BI

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the EV dataset using Pandas.
- Inspected the dataset using `head()`, `info()`, `describe()` and `shape`.
- Checked missing values and duplicate records.
- No missing values or duplicate records were found.
- Detected numerical outliers using the IQR method.
- Analysed skewness of numerical variables.
- Applied `log1p()` transformation to motor power and average driving speed.
- Created `log_motor_power` and `log_avg_speed` features.

## Visualizations

The following visualizations were created:

- Distribution of EV Battery Capacity
- Distribution of EV Motor Power
- Distribution of EV Vehicle Weight
- Battery Capacity vs Real World Range
- Traffic Condition vs Real World Range
- Motor Efficiency vs Real World Range
- ARAI Certified Range vs Real World Range
- Vehicle Weight vs Real World Range

## Power BI Dashboards

### Dashboard 1 – EV Specifications and Range Analysis

This dashboard includes:

- Total EV Records
- Average Real World Range
- Average Battery Capacity
- Average Motor Power
- Battery Capacity Distribution
- Motor Power Distribution
- Vehicle Weight Distribution
- Battery Capacity vs Real World Range

### Dashboard 2 – EV Performance and Driving Conditions Analysis

This dashboard includes:

- Average Motor Efficiency
- Average ARAI Certified Range
- Average Driving Speed
- Average Ambient Temperature
- Traffic Condition vs Real World Range
- Motor Efficiency vs Real World Range
- ARAI Certified Range vs Real World Range
- Vehicle Weight vs Real World Range

## Key Insights

- Higher battery capacity generally tends to provide higher real-world driving range.
- Battery capacity alone does not determine real-world range.
- Motor power does not show a strong direct relationship with real-world range.
- Vehicle weight and motor efficiency can influence EV performance.
- Traffic conditions and average driving speed can affect real-world driving range.

## Conclusion

The project shows that real-world EV driving range depends on multiple factors rather than a single specification.

Python was used for data cleaning, preprocessing and analysis, while Power BI was used to present the findings through interactive dashboards.

Overall, the project provides a data-driven understanding of EV specifications, driving conditions and real-world driving range.
