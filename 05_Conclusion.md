# Conclusion

This project examined the macroeconomic factors associated with gold and silver prices using Multiple Linear Regression and ARIMAX models.

## Gold

For the Regression model, the significant macroeconomic variables were:

- U.S. Dollar Index (DXY) – p-value: 0.26%
- Geopolitical Risk Index (GPRHT) – p-value: 0.05%
- S&P 500 – p-value: 0.00%

For the ARIMAX model, the significant variables were:

- U.S. Dollar Index (DXY) – p-value: 0.00%
- Change in Inflation – p-value: 0.20%

The forecasting accuracy improved significantly when ARIMAX was used.

- Regression MAE: 1,022.33
- ARIMAX MAE: 136.79

This shows that incorporating historical price movements and time-series effects considerably improved the forecasting accuracy for gold.

## Silver

For the Regression model, the significant macroeconomic variables were:

- Oil Price – p-value: 0.00%
- S&P 500 – p-value: 0.00%

For the ARIMAX model, the significant variables were:

- U.S. Dollar Index (DXY) – p-value: 1.60%
- Interest Rate – p-value: 5.00%

The ARIMAX model also produced better forecasting accuracy for silver.

- Regression MAE: 16.79
- ARIMAX MAE: 4.18

This shows that accounting for historical price movements and time-series effects improved the forecasting accuracy for silver.

## Overall Findings

The results show that different macroeconomic variables are associated with gold and silver prices.

For gold, DXY was significant in both the Regression and ARIMAX models, while other significant factors differed between the two models.

For silver, the Regression model identified Oil Price and the S&P 500 as significant, while the ARIMAX model identified DXY and Interest Rate.

Overall, ARIMAX achieved a lower MAE for both gold and silver compared with Multiple Linear Regression, indicating better forecasting performance when time-series effects were included.
