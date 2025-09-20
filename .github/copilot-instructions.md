# Copilot Instructions for Urban Air Quality Trends Analysis

## Project Overview
This project analyzes urban air quality trends in Washington, DC (2019–2021) using public datasets. The workflow is centered around Jupyter Notebooks for data preprocessing, exploratory analysis, and visualization.

## Key Files & Structure
- `final air control analysis .ipynb`: Main notebook for data cleaning, analysis, and visualization.
- `Air_Quality_History.csv`: Source data (referenced in notebooks, not included in repo).
- `README.md`: Brief project description.

## Data Flow & Analysis Steps
1. **Load Data**: Read CSV into pandas DataFrame.
2. **Preprocessing**: Remove duplicates, correct data types, handle missing values, filter by year.
3. **Feature Engineering**: Derive datetime fields, pollutant codes, and best value columns.
4. **Aggregation**: Compute daily/monthly means, pivot tables for pollutants.
5. **Visualization**: Use matplotlib, seaborn, and plotly for histograms, box plots, line charts, pie charts, heatmaps, and scatter plots.
6. **Interpretation**: Annotate findings directly in notebook cells.

## Developer Workflow
- **Run Analysis**: Open the notebook and execute cells sequentially. No build or test scripts are present.
- **Dependencies**: Install via pip if missing: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`.
- **Data File**: Place `Air_Quality_History.csv` in the workspace root.

## Project-Specific Patterns
- All logic is in notebooks; no Python modules or scripts.
- Data cleaning and feature engineering steps are annotated with markdown/code comments for clarity.
- Visualizations are generated inline; interactive plots use plotly.
- Analysis focuses on six core pollutants: PM2.5, O3, NO2, CO, SO2, PM10.
- Seasonal and spatial trends are emphasized in both code and commentary.

## Example Workflow
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
# Load and clean data, then visualize trends
```

## Integration Points
- No external APIs or services; all data is local.
- No custom build/test/debug commands; use Jupyter for all workflows.

## Conventions
- Use markdown cells for explanations and findings.
- Keep code cells focused on one logical step (preprocessing, aggregation, visualization).
- Save cleaned data as `Air_Quality_History_cleaned.csv` if needed.

---
For questions about unclear workflows or missing conventions, please ask for clarification or examples from the notebook.
