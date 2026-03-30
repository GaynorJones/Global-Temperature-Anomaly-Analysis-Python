Global Temperature Anomaly Analysis (Python)

Project Overview

This project analyses global temperature anomaly data using Python.

The dataset contains yearly temperature differences (anomalies) relative to a baseline average (1951–1980), allowing us to identify long-term climate trends.

Features

Load and clean CSV climate data

Handle missing values

Compute:

Average anomaly

Maximum anomaly year

Minimum anomaly year

Visualise temperature trends using matplotlib

Highlight the year with the highest anomaly

Dataset

The dataset contains global land-ocean temperature anomalies from 1880 to present.

Column used: J-D (January–December annual average)

Missing values handled appropriately (e.g. incomplete 2026 data)

Results & Insights

Global temperature anomalies show a clear long-term warming trend.

Warming accelerates significantly after ~1980.

The highest anomalies occur in the most recent years.

Even small anomaly increases (e.g. +0.15°C) represent significant shifts in global climate systems.

![Temperature Trend](temperature_trend.png)

Interpretation

Temperature anomalies measure deviation from a baseline (1951–1980), making them more reliable than absolute temperatures for detecting climate trends.

The data indicates a sustained and accelerating increase in global temperatures, consistent with broader climate science findings.

Technologies Used

Python

Jupyter Notebook

matplotlib

Git & GitHub

How to Run

Clone the repository

Open the notebook:
temperature_anomaly.ipynb

Run all cells

Key Insight

Temperature anomalies provide a clearer view of climate change than raw temperatures, showing how much the Earth is warming relative to a historical baseline.

Updates

## Update Mar 20th 2026
- Added anomaly detection using standard deviation
- Highlighted extreme temperature years
- Introduced decadal averaging for trend smoothing

## Update Mar 30th 2026

Produced multiple plots:
Yearly anomalies (line plot with max/min points annotated)
Scatter plot highlighting extreme years
Decadal averages (bar chart, both pure Python and pandas version)
Introduced pandas for data handling, demonstrating:
Data cleaning with to_numeric and dropna()
Grouping by decades with .groupby('Decade')['J-D'].mean()
Optional features included annotating plots and wrapping pandas preprocessing into a function.

## Temperature Trend (Scatter Plot)

![Temperature Trend](avg_anomalies-scatter-plot.png)

## Extreme Years (Scatter Plot)

![Extreme Years](anomalies_with_extremes.png)

## Decadal Averages (Bar Chart)

![Decadal Python](decadal_avg_anomalies.png)

## Decadal Averages (Pandas)

![Decadal Pandas](decadal_avg_anomalies_pandas.png)

👤 Author

Gaynor Jones
