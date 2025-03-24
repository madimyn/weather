# Weather Data Analysis and Visualization Project

This project gathers weather data for European cities, processes and visualizes it in different ways, and generates an interactive map displaying weather information for each city. The weather data is fetched from the OpenWeatherMap API, and the project uses various Python libraries for data manipulation, visualization, and web mapping.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Overview

The project starts with a Jupyter Notebook (`weather.ipynb`) that performs the following tasks:
1. Collects weather data for cities in Europe using the OpenWeatherMap API.
2. Saves the data in a CSV file (`weather_data.csv`).
3. Creates visualizations, including a temperature histogram and a bar chart of city temperatures.
4. Generates an interactive map (`weather_map.html`) displaying the weather details for each city.

The weather data for European cities is obtained from the [OpenWeatherMap API](https://openweathermap.org/), and additional city information such as geographic coordinates and population comes from the [Geonames dataset](https://public.opendatasoft.com/explore/dataset/geonames-all-cities-with-a-population-1000/).

The final output consists of the following files:
1. **`weather.ipynb`**: The Jupyter Notebook containing the code and data processing logic.
2. **`weather_data.csv`**: A CSV file containing the weather data of the cities.
3. **`city_temperatures.png`**: A bar chart showing city temperatures with gradient colors.
4. **`temperature_histogram.png`**: A histogram showing the distribution of city temperatures.
5. **`weather_map.html`**: An interactive map that visualizes the weather data for each city.

## Features

- **Weather Data Collection**: The script fetches real-time weather data (temperature, humidity, pressure, and weather description) for cities in Europe using the OpenWeatherMap API.
- **Data Storage**: The data is saved into a CSV file (`weather_data.csv`) for later analysis and visualization.
- **Data Visualization**:
  - **Temperature Histogram**: A histogram of city temperatures to analyze temperature distribution across cities.
  - **City Temperatures Bar Chart**: A bar chart with a gradient color scheme that displays the temperature of each city.
- **Interactive Map**: An interactive map created with `folium` that displays markers for each city, showing temperature, humidity, pressure, and weather description when clicked.

## Technologies Used

- **Python 3.x**
- **Libraries**:
  - `requests`: To fetch data from the OpenWeatherMap API.
  - `pandas`: To manipulate and process the data.
  - `matplotlib`: For data visualization, creating histograms and bar charts.
  - `folium`: To create interactive maps.
  - `json`: To handle JSON data.
  - `os`: For file operations.
