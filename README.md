# AQI Exploratory Data Analysis (India, 2015-2020)

Exploratory analysis of daily air quality data across Indian cities to find which cities, seasons, and pollutants drive poor air quality.

## Dataset
- `data/city_day.csv`: 29,531 rows x 16 columns (daily readings, 2015 to mid-2020)

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/AQI_Analysis.ipynb

## Data Cleaning
Rows with missing AQI were dropped. Missing pollutant values were left as NaN.
