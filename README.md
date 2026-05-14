# Post-Pandemic Inflation Forecasting

This project analyzes how well different forecasting models predicted U.S. inflation during and after the COVID-19 pandemic. The goal was to compare simple time-series models with models that include broader macroeconomic indicators.

## Project Summary

The project uses monthly U.S. macroeconomic data from FRED to forecast year-over-year CPI inflation. Models were trained mainly on pre-2020 data and tested on the 2020–2026 period to see how well they handled the post-pandemic inflation surge.

## Data Used

The analysis uses three FRED datasets:

- CPIAUCSL — Consumer Price Index
- UNRATE — Unemployment Rate
- FEDFUNDS — Federal Funds Effective Rate

Inflation was calculated as the year-over-year percentage change in CPI.

## Models Compared

Four forecasting approaches were tested:

- Naive forecast
- Autoregressive model
- Multivariate regression model
- Vector autoregression model

Model performance was evaluated using MAE and RMSE.

## Key Finding

The autoregressive model performed best during the post-2020 test period. This suggests that recent inflation history was more useful for forecasting inflation than adding unemployment and interest rate variables.

The results also showed that all models had larger forecast errors after 2020, meaning inflation became harder to predict during the post-pandemic period.
