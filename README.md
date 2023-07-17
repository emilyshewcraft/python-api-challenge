# python-api-challenge

Module 6 Challenge (for Vanderbilt Data Analytics Bootcamp)

## WeatherPy

Python script using the OpenWeatherMap API to obtain current weather data for a random sample of cities worldwide. Data points are plotted to show the relationship between the following for the entire sample, cities in the northern hemisphere, and cities in the southern hemisphere:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

Additionally, linear regression statistics are displayed on the above plots and relationships for each hemisphere.

> Note: Stack Overflow was used to find code to convert Unix timestamps to datetime.

## VacationPy

Python script using hvPlot to map the cities sampled in WeatherPy, and using the Geoapify API to find the nearest hotel to a selection of those cities with the user's ideal weather conditions.
