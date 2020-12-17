# python-api-challenge

## disclaimer
You'll need to add a api_keys.py file which should contain your api key for the [weather api](https://openweathermap.org/) under weather_api_key as well as your api for the [google places api](https://cloud.google.com/maps-platform/places/) under g_key.

## Part 1: Weather Trends

I graphed latitude on the y axis to be similar to looking at latitude on a map.

Temperature does seem to tend to be warmer as you reach the equator (latitude zero), however this is difficult to see with all of the data plotted.

![Full Data Set](https://wustl.bootcampcontent.com/AEmily96/python-api-challenge/raw/master/Output/TemperatureByLatitude.png)

However, when you plot the northern and southern hemispheres seperately you can see that the temperture increases as latitude reaches zero from either side.

![Northern Hemisphere](https://wustl.bootcampcontent.com/AEmily96/python-api-challenge/raw/master/Output/TemperatureByLatitude_North.png)

![Southern Hemisphere](https://wustl.bootcampcontent.com/AEmily96/python-api-challenge/raw/master/Output/TemperatureByLatitude_South.png)


Wind speed, humidity, and cloud coverage do not seem to have a relationship with latitude though. 


## Part 2: Vacation Spots

All of my prefered vacation spots are currently in the southern hemisphere or near the equator which makes sense since I would like to vacation somewhere warm and it is currently winter in the north and given our analysis on the weather data in part 1, the temperature tends to increase the closer you get to the equator.

![Vacation Spots](https://wustl.bootcampcontent.com/AEmily96/python-api-challenge/raw/master/Output/HeatMapWithMarkers.PNG)