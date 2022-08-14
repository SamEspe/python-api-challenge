# python-api-challenge

## Contributor: Sam Espe

### Overview:

This is my submission for Homework #6 for Data Analytics Boot Camp. There are two Jupyter Notebooks: WeatherPy and VacationPy.

#### WeatherPy

In WeatherPy, I generated a random list of more than 500 cities around the world, and retrieved weather for each city from the OpenWeather API. Using the weather data for these cities, I created scatter plots and linear regressions to investigate relationships between latitude and various weather measurements (maximum temperature, humidity, cloudiness, and wind speed). I saved copies of the various graphs to the file `output_data` as PNGs.

#### VacationPy

In VacationPy, I used the weather data from WeatherPy to find places with pleasant weather (on 8/12/22, when the data was downloaded) that I might want to vacation at. I started by making a heat map using `gmap` of humidity in the 500+ cities from WeatherPy. I then filtered down the list of 500+ cities to a list of 9 places that had what I consider optimal weather (temperature between 65 and 80 degrees Fahrenheit, relative humidity less than 40%, cloudiness less than 30%, and a breeze less than or equal to 7 miles per hour). Using the Google Places API, I found the nearest hotel within 5000 meters of the geographic coordinates of each city, and I made markers on the heat map for each of the final cities with the name of the hotel. Screenshots of the resulting maps are located in the file `map_screenshots` as PNGs.
