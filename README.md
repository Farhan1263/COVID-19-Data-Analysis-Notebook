# COVID-19-Data-Analysis-Notebook
## Overview
This Jupyter Notebook contains an analysis of global COVID-19 case data. It visualizes the progression of confirmed cases, recoveries, and deaths worldwide over time using data from a publicly available dataset.
## Features
- Loads and preprocesses COVID-19 aggregated country-level data
- Computes total global cases by summing confirmed, recovered, and death counts
- Generates a time series plot showing worldwide COVID-19 case trends
## Data Source
The dataset is sourced from:  
`https://raw.githubusercontent.com/datasets/covid-19/master/data/countries-aggregated.csv`
## Requirements

To run this notebook, you'll need:

- Python 3.x
- Jupyter Notebook or JupyterLab
- pandas
- matplotlib

The notebook produces a line chart showing:
- Total confirmed cases
- Recoveries
- Deaths  
over time worldwide, using the `fivethirtyeight` matplotlib style.

