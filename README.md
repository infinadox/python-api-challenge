# Weather and Vacation Analysis

## Overview

This project consists of two main parts: 

1. **WeatherPy**: Analysis of weather data across 500+ cities of varying distances from the equator.
2. **VacationPy**: Visualization of vacation destinations based on ideal weather conditions, including finding nearby hotels.

## Project Structure

- **WeatherPy.ipynb**: Jupyter notebook for analyzing the relationship between various weather parameters and latitude.
- **VacationPy.ipynb**: Jupyter notebook for visualizing vacation spots and nearby hotels using the Geoapify API.
- **output_data/cities.csv**: Dataset containing weather and location data for various cities.
- **README.md**: Project description and sources.

## Data Sources and Libraries Used

### WeatherPy
- **OpenWeatherMap API**: Used to retrieve weather data for multiple cities.
- **Citipy Library**: Used to generate city names based on random latitude and longitude combinations.
- **Pandas**: For data manipulation and storage.
- **Matplotlib**: For visualizing data through scatter plots.
- **SciPy Stats**: For computing linear regression to analyze relationships between weather variables and latitude.

### VacationPy
- **Geoapify API**: Used to find nearby hotels within a specified radius of each city.
- **hvPlot and GeoViews**: Used for creating interactive map visualizations.
- **Pandas**: For data manipulation and storage.
- **Matplotlib**: For visualizing data.
