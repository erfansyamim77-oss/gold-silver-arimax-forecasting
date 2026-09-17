# Conclusion

This project examined the macroeconomic factors associated with gold and silver prices using Multiple Linear Regression and ARIMAX models.

## Gold

The analysis shows that several macroeconomic variables were significantly associated with gold prices.

For the Regression model, the significant factors were:

- U.S. Dollar Index (DXY) – p-value: 0.26%
- Geopolitical Risk Index (GPRHT) – p-value: 0.05%
- S&P 500 – p-value: 0.00%

For the ARIMAX model, the significant factors were:

- U.S. Dollar Index (DXY) – p-value: 0.00%
- Change in Inflation – p-value: 0.20%

Overall, the main macroeconomic factors identified for gold were DXY, geopolitical risk, the S&P 500, and changes in inflation.

DXY was particularly important because it was significant in both the Regression and ARIMAX models.

The forecasting accuracy also improved significantly with ARIMAX:

- Regression MAE: 1,022.33
- ARIMAX MAE: 136.79

This suggests that including historical price movements and time-series effects improved the ability to forecast gold prices.

## Silver

For silver, the significant macroeconomic factors were different from those identified for gold.

For the Regression model, the significant factors were:

- Oil Price – p-value: 0.00%
- S&P 500 – p-value: 0.00%

For the ARIMAX model, the significant factors were:

- U.S. Dollar Index (DXY) – p-value: 1.60%
- Interest Rate – p-value: 5.00%

Overall, the main macroeconomic factors identified for silver were oil prices, the S&P 500, DXY, and interest rates.

The forecasting accuracy also improved when ARIMAX was used:

- Regression MAE: 16.79
- ARIMAX MAE: 4.18

This suggests that accounting for historical price movements and time-series effects improved the forecasting performance for silver.

## Overall Findings

The results suggest that gold and silver respond to different macroeconomic conditions.

For gold, the main factors identified were DXY, geopolitical risk, the S&P 500, and inflation changes.

For silver, the main factors identified were oil prices, the S&P 500, DXY, and interest rates.

ARIMAX achieved a lower MAE for both commodities compared with Multiple Linear Regression, indicating better forecasting performance when time-series effects were included.
