# Python-API-Challenge

WEATHERPY
This Python code randomly selects and creates a list of over 500 cities from around the world. The code gathers data 
from the OpenWeatherMap API to create a weather model across world cities. 

The data is used to graph the relationships listed below:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Then, the plots are separated into Northern Hemisphere and Southern Hemisphere and a linear regression 
is run on each relationship.
- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude


VACATIONPY
This code uses jupyter-gmaps and the Google Places API to analyze weather data and does the following:
- create a heat map that displays humidity for various cities
- narrows down a DataFrame to find ideal weather conditions
- uses Google Places API to find the first hotel for each city within 5000 meters of given coordinates
- plot the hotels on top of the humidity heat map
