# python-api-challenge
Module 6 Challenge - Use the OpenWeatherMap API to pull current weather information for several hundred cities selected based on random longitudes and latitudes.  Then create several plots and regression lines that compare latitude against various weather information.  Create a map with every city and its weather information.  Next, use the weather data to narrow the city search down to lesson than 20 cities.  Finish by using the Geoapify API to find hotels within 10 km of each city in the smaller subset, and plot these cities with their humidity and hotel information on a map.

## Requirements for running the code
- An api_keys.py document is assumed to be included within the WeatherPy folder and the VacationPy folder.  You will need to create these files on your own device.  You will need to store in these files API keys from OpenWeatherMap and Geoapify in order to successfully run the programs.

## Running the code
- The first code to run will be WeatherPy.ipynb which will handle randomly selecting your cities and pulling the relevant weather information.
- The second code to run will be VacationPy.ipynm which will handle mapping the cities and pulling city information.
- VacationPy will narrow down the selection of cities based on the following information:
1. Maximum temperature being between 21 and 27 degrees Celsius (70 and 81 degrees Fahrenheit)
2. Wind speed less than 4.5 m/s (10 mph)
3. Less than 15% cloud cover
