# Interactive COVID-19 Data Analysis

## Project Overview
This project provides an **interactive analysis of global COVID-19 trends** using Python and Plotly. It tracks daily infections, recoveries, and regional patterns, providing insights for pandemic monitoring and policy decisions.

## Objective
- Analyze COVID-19 case data to identify trends and peaks.
- Visualize data interactively with zoom, pan, and hover features.
- Compare single-country and multi-country trends.
- Provide actionable insights for public health policy.

## Dataset
- **Source:** [Johns Hopkins COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19)
- **Columns:** Date, Country, ConfirmedCases, Deaths, Recovered
- Data is preprocessed for missing values and proper time-series formatting.

## Methodology
1. **Data Collection:** Imported global COVID-19 case data and verified accuracy.
2. **Data Preprocessing:** Handled missing values, converted date columns for time-series analysis.
3. **Exploratory Data Analysis (EDA):** 
   - Line charts show case growth over time.
   - Heatmaps highlight most affected regions.
4. **Feature Selection:** Focused on factors like population density and testing rates.
5. **Interactive Visualization:** 
   - Single-country trend plots.
   - Multi-country comparison plots with dropdowns.
   - Hover tooltips display detailed information.

## Key Findings
- Identified infection peaks and high-risk regions.
- Observed differences in growth patterns among countries.
- Rolling averages helped visualize long-term trends.

## Tools & Libraries
- Python
- Pandas
- Plotly
- Matplotlib
- Google Colab / Jupyter Notebook
- FPDF (for PDF report generation)

## How to Run
1. Open the notebook in Google Colab:  
[Run Notebook in Colab](https://colab.research.google.com/drive/1mSTPhff5lVLquq7ZO9hLz8o299I7PJLR?usp=sharing)

2. Install required libraries if not already available:
```python
!pip install pandas plotly fpdf matplotlib
