# Conclusion

This project examined the macroeconomic factors associated with gold and silver prices using Multiple Linear Regression and ARIMAX models.

## Gold

For the Regression model, the significant macroeconomic variables were:

- U.S. Dollar Index (DXY) – p-value: 0.26%
- Geopolitical Risk Index (GPRHT) – p-value: 0.05%
- S&P 500 – p-value: 0.00%

For the ARIMAX model, the significant variables were:

- U.S. Dollar Index (DXY) – p-value: 0.000
- Change in Inflation – p-value: 0.002

The forecasting accuracy improved significantly when ARIMAX was used.

- Regression MAE: 1,022.33
- ARIMAX MAE: 136.79

This shows that incorporating historical price movements and time-series effects considerably improved the forecasting accuracy for gold.

## Silver

For the Regression model, the significant macroeconomic variables were:

- Oil Price – p-value: 0.00%
- S&P 500 – p-value: 0.00%

For the ARIMAX model, the significant variables were:

- U.S. Dollar Index (DXY) – p-value: 0.016
- Interest Rate – p-value: 0.05

ARIMAX also produced a lower forecasting error for silver.

- Regression MAE: 16.79
- ARIMAX MAE: 4.18

This indicates that accounting for time-series behaviour improved the forecasting accuracy for silver.

## Overall Findings

The results show that different macroeconomic variables are associated with gold and silver prices.

DXY was particularly important for gold because it remained statistically significant in both the Regression and ARIMAX models. For silver, the significant variables changed after historical price movements were taken into account.

Overall, ARIMAX achieved a lower MAE for both gold and silver compared with Multiple Linear Regression, suggesting that including time-series effects provides better forecasting performance for precious metal prices.
