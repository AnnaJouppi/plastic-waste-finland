# Finland Packaging Waste Analysis & Prediction (2014-2026)

This project analyzes the trend of packaging waste generation per person in Finland and predicts future waste levels for the years 2024–2026 using Linear Regression.

Data Cleaning:
* Renames unclear dataset columns to understandable English.
* Specifically excludes the years 2020 and 2021 (COVID-19 pandemic).
  * The reason: The pandemic caused an abnormal spike in packaging waste (due to increased takeout, online shopping, etc.) which distorts the long-term trend analysis.

Visualization:
* Plots the historical waste data per person using a bar chart.

Prediction:
 * Uses a Linear Regression model (sklearn) to predict waste generation for 2024, 2025, and 2026.
