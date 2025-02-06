# Household Deposits Forecast

This project uses time series forecasting to predict the future household deposits in Romania and Denmark, using **ARIMA** and **ARIMA-GARCH** models. The notebook contains the data processing steps, model fitting, and forecasting.

## Project Overview

This repository provides an analysis of household deposits from Romania and Denmark, using time series data from **January 2007 to December 2024**, respectively **January 2003 to December 2024**. The main goal of the project is to forecast future household deposits, taking into account both the trend (via ARIMA) and volatility (via ARIMA-GARCH).

## Key Features:
- **Data Preprocessing**: The data is processed and adjusted for the date format.
- **ARIMA Model**: A simple ARIMA model is applied to forecast future deposits.
- **ARIMA-GARCH Model**: A more advanced ARIMA-GARCH model is used to account for volatility in the forecast.
- **Forecasting**: The project provides a 12-month forecast for household deposits from December 2024 onward.
- **Visualization**: The forecast results are visualized with confidence intervals, allowing for an understanding of the forecast uncertainty.

Files:
Depo.ipynb: Jupyter Notebook containing the analysis, model fitting, and forecast generation for both Romania and Denmark.
data/: Folder containing the data files (IFMDL.xls for Romania and 20252612455521153735DNPINDK.xlsx for Denmark), which includes the historical household deposits for each country.

## Data sources:
- https://www.bnro.ro/Depozitele-gospodariilor-populatiei-5794.aspx
- https://www.nationalbanken.dk/en/news-and-knowledge/data-and-statistics/banking-and-mortgage-lending/deposits (total Household deposits)
