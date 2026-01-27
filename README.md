# Building Energy Analytics Pipeline

## Project Overview
Developed a full data pipeline to process electricity consumption data for 172 building meters in Portugal, merged with weather data, and produced an analytics-ready dataset.

## Dataset
- Energy CSV: loureiro_energy.csv
- Weather CSV: weather_aveiro_final.csv
- Final cleaned dataset: final_energy_weather.csv

## Steps Performed
1. Loaded CSV files into Pandas
2. Parsed timestamps for both datasets
3. Reshaped 172 energy meter columns from wide → long format
4. Cleaned missing and negative energy values
5. Aggregated total building energy consumption
6. Merged energy data with weather features
7. Handled remaining missing values via forward/backward fill
8. Saved analytics-ready dataset
9. Created exploratory visualizations

## Technologies Used
- Python, Pandas, NumPy
- Matplotlib / Seaborn (optional)
- Google Colab

## Insights / Use Cases
- Ready for energy consumption trend analysis
- Correlation with weather patterns
- Basis for predictive modeling and dashboards
