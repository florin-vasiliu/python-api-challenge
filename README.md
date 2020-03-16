# Python API Homework - What's the Weather Like?
## Exploring weather trends around the world
In order to identify weather trends as a function of location on the globe, the parameters selected for characterizing weather were temperature, humidity, cloudiness, and wind speed. The places used for weather data collection were cities selected on the whole range latitudes, and random longitudes. 

<img src=WeatherPy/Images/CitiesDataSetEg.PNG width=500>|
:-------------------------:|
Extract from the data used for analysis|

The charts below represent the weather parameters in relation to the latitude of the selected cities. The only parameter which seems to be dependent of the latitude is the temperature. The shape of the correlation seems to have an inflection point at zero degrees latitude, which corresponds to the equator.

<img src=WeatherPy/Images/Cloudiness%20%5B%25%5D_vs_latitude.png> | <img src=WeatherPy/Images/Humidity%20%5B%25%5D_vs_latitude.png>
:-------------------------:|:-------------------------:
<img src=WeatherPy/Images/Temperature%20%5BF%5D_vs_latitude.png>  | <img src=WeatherPy/Images/Wind%20Speed%20%5Bmph%5D_vs_latitude.png> 

By further dividing the data into subsets pertaining to the southern hemisfere (latitude less than zero degrees) and the northern hemisfere (latitude greater than zero degrees), it seems that the temperature is strongly influenced by the latitude especially in the nothern hemisfere. This stronger correlation might be due to a smaller number of cities available for the whole range of latitudes in the southern hemisfere (-90 to 0 degrees).

<img src=WeatherPy/Images/Northern_Hemisphere-Cloudiness%20%5B%25%5D_vs_latitude.png> | <img src=WeatherPy/Images/Southern_Hemisfere-Cloudiness%20%5B%25%5D_vs_latitude.png>
:-------------------------:|:-------------------------:
<img src=WeatherPy/Images/Northern_Hemisphere-Humidity%20%5B%25%5D_vs_latitude.png>  | <img src=WeatherPy/Images/Southern_Hemisfere-Humidity%20%5B%25%5D_vs_latitude.png> 
<img src=WeatherPy/Images/Northern_Hemisphere-Temperature%20%5BF%5D_vs_latitude.png> | <img src=WeatherPy/Images/Southern_Hemisfere-Temperature%20%5BF%5D_vs_latitude.png> 
<img src=WeatherPy/Images/Northern_Hemisphere-Wind%20Speed%20%5Bmph%5D_vs_latitude.png> | <img src=WeatherPy/Images/Southern_Hemisfere-Wind%20Speed%20%5Bmph%5D_vs_latitude.png> 

## Choosing best vacation places among cities analyzed

From the dataset of cities used to analyze the global weather trend, a heat map of the humidity has been plotted to determine ideal places to go in vacation.

<img src=VacationPy/Images/HeatMap.png>|
:-------------------------:|
Heat map of the humidity for the cities analyzed|

The ideal cities for vacation were selected based on the following criteria:
 - Temperature: between 73 and 78 [degF];
 - Cloudiness: only cities with no clouds (0[%] cloudiness);
 - Wind speed: only cities with a wind speed less than 5[mph].

Finally, the nearest hotels for the ideal cities for vacation have been ploted over the heat map.

<img src=VacationPy/Images/HeatMap%26NearestHotels.png>|
:-------------------------:|
Nearest hotels for the ideal places for vacation|

## References
https://openweathermap.org/api - source for all weather related analysis 

https://cloud.google.com/maps-platform/places - source for maps and places
