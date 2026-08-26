# Weather ETL Pipeline

## 1. Project Overview

This project demonstrates a simple ETL (Extract, Transform, Load) pipeline using real-time weather data from the OpenWeather API. Weather data was collected for Johannesburg, Cape Town, and Durban, then transformed using Pandas and saved as a CSV file for analysis.

## 2. Data Source

The weather data was collected using the OpenWeather API. The API provides current weather information for cities around the world.

The cities used in this project are:
- Johannesburg
- Cape Town
- Durban

## 3. Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Requests
- OpenWeather API

## 4. ETL Process

### Extract

Weather data was extracted from the OpenWeather API for Johannesburg, Cape Town, and Durban using Python and the Requests library.

### Transform

The extracted weather data was converted into a Pandas DataFrame, checked for missing values and duplicates, and prepared for analysis. Relevant weather variables such as temperature, humidity, weather condition, and wind speed were selected.

### Load

The transformed weather data was saved as `processed_weather_data.csv` for further analysis and use.

## 5. Steps Taken

1. Set up the OpenWeather API and selected three cities for data collection.
2. Created a Python function to extract weather data for each city.
3. Extracted the weather data using the OpenWeather API.
4. Stored the extracted data in a Python list.
5. Converted the data into a Pandas DataFrame.
6. Checked the dataset for missing values and duplicate records.
7. Transformed and prepared the relevant weather variables.
8. Analysed temperature, humidity, weather conditions, and wind speed.
9. Calculated the average temperature across the three cities.
10. Saved the transformed dataset as `processed_weather_data.csv`.

## 6. Key Findings

- Cape Town had the highest temperature at 24.94°C.
- Durban had the lowest temperature at 21.17°C.
- The average temperature across the three cities was 23.59°C.
- Durban had the highest humidity at 71%.
- Cape Town had the highest wind speed at 4.12 m/s.
- Johannesburg and Cape Town had overcast clouds, while Durban had broken clouds.

## 7. Project Files

- `weather_etl_pipeline.ipynb` – Jupyter Notebook containing the complete ETL process and analysis.
- `processed_weather_data.csv` – Transformed weather dataset.
- `.gitignore` – Prevents the `.env` file from being uploaded to GitHub.

## 8. Security

The OpenWeather API key is stored locally in a `.env` file and is not included in this repository. The `.gitignore` file prevents the `.env` file from being uploaded to GitHub.
