# 📊 Advertising Sales Forecasting with R

This project focuses on time series forecasting of advertising sales data using various statistical and machine learning techniques in R.

## 🗂️ Project Overview

The analysis aims to:
- Load and explore a dataset (`advertising.csv`) with monthly sales figures.
- Visualize and understand sales trends using plots and summary statistics.
- Apply different forecasting models including:
  - Naïve Forecast
  - ARIMA
  - Exponential Smoothing
- Compare model performances using residual plots and accuracy metrics.

## 🧰 Tools & Libraries Used

- **R** with the following packages:
  - `dplyr`, `ggplot2` – for data manipulation and visualization
  - `forecast`, `fpp`, `fpp2` – for time series modeling
  - `TTR`, `UsingR` – for technical analysis and utility functions

## 📈 Key Steps in Analysis

1. Load sales data from CSV.
2. Convert sales data into a time series object.
3. Perform exploratory analysis: plots, ACF, boxplots, histograms.
4. Apply and visualize forecasts using:
   - Naïve model
   - Seasonal decomposition
   - ARIMA
   - Holt-Winters
5. Evaluate residuals and forecasting accuracy.

## 📄 How to Run

1. Open `BF_PROJECT.Rmd` in **RStudio**.
2. Make sure the dataset `advertising.csv` is correctly placed at the path used in the script.
3. Click **Knit** to generate the HTML or Word document.
4. Review visualizations and forecast outputs.

## 📌 Author

**Shrey Shah**  

---

