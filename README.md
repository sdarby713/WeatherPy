# WeatherPy

What's the weather like as we approach the equator?  Here is a demonstration of how we might find out and show it.

First step is to generate a random list of latitudes and longitudes and use that to generate a list of cities around the world.  To reduce the bias toward coastal cities inherent in that method, I require cities to be within one degree of the randomly generated longitude and latitude.

Then, process APIs for our list of cities from api.openweathermap.org and gather data for max temperatures, humidity, cloudiness and wind speed for the cities we find there.

Finally, plot each of these data points separately against latitude.  We'll save these plots into individual files.
