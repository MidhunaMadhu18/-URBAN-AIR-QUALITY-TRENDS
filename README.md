
# Analysis of Urban Air Quality Trends in Washington, DC (2019–2024)

## Project Overview
This project analyzes urban air quality trends and influences in Washington, DC, using hourly pollutant and meteorological data from 2019 to 2024. The goal is to understand how air pollution levels have changed over time and identify factors associated with those changes.

## Dataset
- **Source:** Air Quality History – Washington, DC (Data.gov)
- **File:** `Air_Quality_History.csv`
- **Contents:** Hourly measurements from five monitoring stations, including:
  - Fine particulate matter (PM₂.₅)
  - Ozone (O₃)
  - Nitrogen dioxide (NO₂)
  - Carbon monoxide (CO)
  - Sulfur dioxide (SO₂)
  - Particulate coarse matter (PM₁₀)
  - Meteorological parameters: temperature, humidity, wind, pressure

## Analysis Steps
1. **Data Preprocessing:**
	- Remove duplicates
	- Correct data types
	- Handle missing values
2. **Feature Engineering:**
	- Create compact pollutant codes
	- Derive date, year, month fields
	- Select best measurement per row
3. **Exploratory Data Analysis:**
	- Univariate and bivariate statistics
	- Correlation analysis
	- Aggregation by day and month
4. **Visualization:**
	- Histograms, box plots, line charts, pie charts, heatmaps, bar plots, scatter plots
	- Interactive visualizations with Plotly

## Key Findings
- Ozone (O₃) shows strong seasonality, peaking in summer.
- PM₂.₅ tends to be higher in summer and lower in winter.
- NO₂ and CO concentrations are higher near roadways.
- Weather conditions (temperature, humidity) strongly influence pollution levels.
- Washington, DC’s air quality reflects typical urban patterns: summer smog and winter soot.

## How to Use
1. Open the notebook file for step-by-step analysis and visualizations.
2. Review code and markdown cells for explanations and results.
3. Use the cleaned dataset for further modeling or research.

---
For more details, see the notebook: `final air control analysis .ipynb`
