# Individual Household Electric Power Consumption

## Project Overview
This project analyzes the electric power consumption of an individual household over a 4-year period. The goal of this project is to uncover insights about power usage patterns, build predictive models, and perform detailed time-series analysis to assist in better power management and prediction of power demand.

## Dataset
The dataset contains measurements of electric power consumption from a single household, recorded between December 2006 and November 2010 (47 months). The data includes the following attributes:

- **Date**: The date of the observation.
- **Time**: The time of the observation.
- **Global_active_power**: The total active power consumed by the household in kilowatts (kW).
- **Global_reactive_power**: The reactive power consumed by the household in kilovars (kVAR).
- **Voltage**: The average voltage (V).
- **Global_intensity**: The average current intensity (A).
- **Sub_metering_1**: Energy sub-metering for the kitchen (in watt-hours).
- **Sub_metering_2**: Energy sub-metering for the laundry (in watt-hours).
- **Sub_metering_3**: Energy sub-metering for the electric water heater and air conditioning (in watt-hours).

The dataset contains a few missing values that have been handled using forward filling techniques to ensure smooth analysis.

## Project Goals
1. **Exploratory Data Analysis (EDA)**:
   - Visualizing trends over time.
   - Understanding consumption patterns across different appliances.
   - Analyzing daily, monthly, and seasonal power consumption trends.
   
2. **Time-Series Analysis**:
   - Investigating trends and seasonality in energy consumption.
   - Resampling the data to observe consumption on different time scales (daily, weekly, etc.).

3. **Data Visualization**:
   - Creating interactive charts and graphs using **Power BI** and **Tableau** to visually represent power usage trends and highlight anomalies.


## Tools & Technologies
- **Languages**: Python (Pandas, NumPy)
- **Visualization Tools**: Power BI, Tableau, Matplotlib, Seaborn
- **Others**: Jupyter Notebooks, Git, GitHub

## Key Insights
- **Global_active_power** consumption shows strong seasonal patterns with peaks during winter months.
- **Sub_metering_3** (electric water heater and AC) has the highest energy usage, especially during the summer.
- **Correlation analysis** reveals that `Global_active_power` is highly correlated with `Global_intensity` and `Voltage`.

## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Smolbitties/Individual-Household-Electric-Power-Consumption.git

This README is tailored for the project and provides an overview of the goals, tools, structure, and insights. You can paste this directly into your `README.md` file!

