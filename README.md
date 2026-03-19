# 🌤️ Weather Data Analysis 📊

Welcome to the **Weather Data Analysis** project! This repository contains an Exploratory Data Analysis (EDA) on historical weather data. We dive deep into uncovering patterns, calculating trends, and understanding the relationships between different meteorological factors! 🚀✨

---

## 📂 Project Structure

To keep things neat and tidy, the project is organized into specific directories:

- 📓 **`notebooks/`** 
  - `main.ipynb`: The core Jupyter Notebook! It's structured with step-by-step EDA containing:
    1. 📦 Importing Libraries
    2. 📥 Loading Dataset
    3. 🔍 Dataset Overview & Description
    4. 🧹 Data Cleaning
    5. 🔬 Analysis (Univariate & Bivariate)
    6. ⏳ Temporal Analysis
    7. 💡 Key Statistical Findings
- 📁 **`data/`**
  - `weatherHistory.csv`: The historical dataset used for this project *(Move your file here if it's currently at the root!)*.
- 🎨 **`visuals/`**
  - Stored inside this directory are all the cool generated visualizations (`fig*.png`).

---

## 📋 Dataset Features

The dataset (`weatherHistory.csv`) brings a variety of awesome weather attributes:

- 📅 **Formatted Date:** Date and exact time of the observation.
- ☁️ **Summary:** A quick description of the weather condition!
- 🌧️ **Precip Type:** What's falling from the sky (e.g., rain, snow).
- 🌡️ **Temperature (C):** The actual temperature in Celsius.
- 🧥 **Apparent Temperature (C):** How it *actually* feels outside!
- 💧 **Humidity:** The relative humidity in the air.
- 💨 **Wind Speed (km/h) & Bearing (degrees):** Everything about the wind.
- 👁️ **Visibility (km):** How far we can clearly see!
- 🌥️ **Loud Cover:** The fraction of the sky obscured by clouds.
- 🎈 **Pressure (millibars):** Atmospheric pressure.
- 📝 **Daily Summary:** A neat summary of the day's weather.

---

## 🖼️ Visualizations Highlight

All magical charts have been generated and neatly tucked into the **`figures/`** folder! Here are the showstoppers:

- 📊 **Distributions:** Histograms showing temperature, humidity, wind speed, and pressure (`fig1_distributions.png`, `fig4_histograms.png`).
- 🏆 **Top 10 Categories:** Which weather conditions are the most common? (`fig2_summary_categories.png`).
- ☔ **Precipitation Types:** A breakdown of rain vs. snow (`fig3_precip_type.png`).
- 🗺️ **Correlation Heatmap:** The ultimate matrix of how weather factors interact (`fig4_correlation_heatmap.png`).
- 🔥 **Temp vs. Apparent Temp:** Seeing the difference between actual vs. feels-like (`fig5_temp_vs_apparent.png`).
- 💧 **Temp & Humidity by Precip:** Box plots breaking down features by rain/snow (`fig6_temp_humidity_by_precip.png`).
- 🌪️ **Wind Speed vs. Visibility:** Scatter plot fun! (`fig7_wind_visibility.png`).
- 📅 **Temporal Trends:** Monthly comparisons (`fig8_combined_monthly.png`) and hourly temperature patterns (`fig10_hourly_temp.png`).

---

## 🚀 Getting Started

Ready to explore the data yourself? Here's how to jump right in:

1. 🐍 **Python & Jupyter:** Make sure you have Python and Jupyter Notebook installed!
2. 📦 **Dependencies:** Install the required data science libraries: `pandas`, `matplotlib`, and `seaborn`.
3. 🏃‍♂️ **Run the Notebook:** Open up `notebooks/main.ipynb` (or `main.ipynb` at the root) and run all cells to generate the insights!

Happy analyzing! 🎉👨‍💻👩‍💻
