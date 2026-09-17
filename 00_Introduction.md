# Macroeconomic Drivers of Gold & Silver Prices

### Regression and ARIMAX Analysis

This project examines the relationship between macroeconomic factors and gold and silver prices using Regression and ARIMAX models.

For regression, you can click on view raw to download the folder.

The main objective is to identify which macroeconomic factors are significantly associated with gold and silver prices over time, while accounting for their past model errors for forcasting.

## Macroeconomic Variables

The analysis includes six macroeconomic variables:

- Interest Rate
- Inflation
- Oil Price
- U.S. Dollar Index (DXY)
- Geopolitical Risk Index (GPR)
- S&P 500

## Methodology

Monthly data from **1975–2024** was used for model development.

Two models were applied:

### 1. Multiple Linear Regression

Used to examine the relationship between macroeconomic variables and gold and silver prices.

### 2. ARIMAX

Used to analyse macroeconomic variables while incorporating historical price movements and time-series effects.

Model results were evaluated based on:

- Coefficient direction
- Statistical significance (p-value)
- Model diagnostics
- Out-of-sample performance

Data from **2025** was used for out-of-sample testing to assess model performance.

## Research Objective

The primary purpose of this analysis is to understand the key macroeconomic factors associated with gold and silver price movements rather than simply predict future commodity prices.

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Microsoft Excel
