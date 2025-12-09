# Analysis of U.S. Domestic Passenger Traffic Trends

This repository contains a time series forecasting analysis of U.S. domestic airline passenger traffic using historical monthly data. 
The project applies exponential smoothing and related forecasting models to identify long-term trends, seasonality, and future passenger demand.

## Project Objectives
- Analyze historical U.S. domestic passenger traffic patterns
- Identify long-term trends and seasonal behavior
- Build and validate a suitable forecasting model
- Generate short-term forecasts for future passenger demand
- Provide actionable insights for aviation industry stakeholders

## Data Description
- **Variable of Interest:** Monthly U.S. domestic airline passengers  
- **Frequency:** Monthly  
- **Source:** Publicly available U.S. aviation/transportation statistics  
- **Time Period:** 2010 - 2025

## Methodology
- Time series decomposition
- Trend and seasonality analysis
- Holt exponential smoothing model
- Model validation using residual diagnostics
- Short-term forecasting and interpretation

## Key Findings
- Passenger traffic exhibits a strong long-term upward trend and clear annual seasonality.
- The Holt model performs well for short-term forecasting.
- Forecasts suggest continued growth with predictable seasonal fluctuations.
- While the model captures historical patterns well, it cannot predict structural shocks (e.g., pandemics).

## Software & Packages Used
- R
- Quarto (.qmd)
- fpp3
- fable
- fable.prophet
- lubridate
- readr
- readxl

## Repository Structure
├── analysis.qmd            # Main Quarto file containing the full analysis
├── data/                   # Raw and processed datasets (CSV/Excel files)
├── output/                 # Rendered PDF report
├── README.md               # Project overview and instructions
