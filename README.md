# WeatherPy & VacationPy

## Project Overview

### WeatherPy
WeatherPy visualizes the weather of over 500 cities worldwide by utilizing geographic coordinates and current weather data from the OpenWeatherMap API. Scatter plots are created to illustrate relationships between weather variables (temperature, humidity, cloudiness, wind speed) and latitude. Linear regressions are computed to analyze these relationships in both Northern and Southern Hemispheres.

### VacationPy
VacationPy leverages the weather data obtained in WeatherPy to assist in planning future vacations. It utilizes `geoViews` and the Geoapify API to create map visualizations showing cities that meet specific weather criteria (e.g., ideal temperature, low wind speed, clear skies). It also identifies nearby hotels using the Geoapify API and plots them on the map with hover information displaying hotel details.

## Tools and Libraries Used
- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Requests
- citipy
- `geoViews`
- Geoapify API

## File Structure
- `WeatherPy.ipynb`: Jupyter Notebook containing the WeatherPy project.
- `VacationPy.ipynb`: Jupyter Notebook containing the VacationPy project.
- `output_data/`: Directory containing CSV files generated from both projects.
- `images/`: Directory containing scatter plot images and map visualizations generated from the projects.
- `README.md`: This README file providing an overview and findings for both WeatherPy and VacationPy.

## Summary of Findings

### WeatherPy
- **Temperature vs. Latitude:** Temperatures generally decrease away from the equator.
- **Humidity vs. Latitude:** No clear correlation observed between humidity and latitude.
- **Cloudiness vs. Latitude:** Cloudiness shows no significant relationship with latitude.
- **Wind Speed vs. Latitude:** Wind speeds tend to be higher in polar regions compared to near the equator.

### VacationPy
- **Map Visualization:** Cities meeting ideal weather conditions are shown on the map with markers sized by humidity.
- **Hotel Information:** The first nearby hotels are plotted on the map with hover information displaying hotel details.