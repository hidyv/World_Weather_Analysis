# World_Weather_Analysis

This project has two parts:
The first part is to create visualization to analyze the weather data of over 500 cities of varying distances from the equator. The second part is to identify the ideal vacation spot based on the weather information of the cities.

Part 1: WeatherPy 
The citipy Python library, the OpenWeatherMap API, Matplotlib used create the scatter plots depicting relationships:
•	Latitude vs. Temperature
•	Latitude vs. Humidity
•	Latitude vs. Cloudiness
•	Latitude vs. Wind Speed

Linear regression for each relationship is computed. Separate plots for created for both northern and southern hemispheres.

•	Northern Hemisphere: Temperature vs. Latitude
•	Southern Hemisphere: Temperature vs. Latitude
•	Northern Hemisphere: Humidity vs. Latitude
•	Southern Hemisphere: Humidity vs. Latitude
•	Northern Hemisphere: Cloudiness vs. Latitude
•	Southern Hemisphere: Cloudiness vs. Latitude
•	Northern Hemisphere: Wind Speed vs. Latitude
•	Southern Hemisphere: Wind Speed vs. Latitude

Part 2: VacationPy

For this part of the project, output from the WeatherPy, Jupyter notebooks, hvplot_geoViews, library and Geoapify API are used to create map visualizations
