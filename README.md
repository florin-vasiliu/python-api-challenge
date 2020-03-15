# Python API Homework - What's the Weather Like?
## Exploring weather trends around the world
In order to identify weather trends as a function of location on the globe, the parameters selected for characterizing weather were temperature, humidity, cloudiness, and wind speed. The places used for weather data collection were cities selected on the whole range latitudes, and random longitudes. 

The charts below represent the weather parameters in relation to the latitude of the selected cities. The only parameter which seems to be dependent of the latitude is the temperature. The shape of the correlation seems to have an inflection point at zero degrees latitude, which corresponds to the equator.

<img src=WeatherPy/Images/Cloudiness%20%5B%25%5D_vs_latitude.png> | <img src=WeatherPy/Images/Humidity%20%5B%25%5D_vs_latitude.png>
:-------------------------:|:-------------------------:
<img src=WeatherPy/Images/Temperature%20%5BF%5D_vs_latitude.png>  | <img src=WeatherPy/Images/Wind%20Speed%20%5Bmph%5D_vs_latitude.png> 

By further dividing the data into subsets pertaining to the southern hemisfere (latitude less than zero degrees) and the northern hemisfere (latitude greater than zero degrees), it seems that the temperature is strongly influenced by the latitude especially in the nothern hemisfere.

<img src=WeatherPy/Images/Northern_Hemisphere-Cloudiness%20%5B%25%5D_vs_latitude.png> | <img src=WeatherPy/Images/Southern_Hemisfere-Cloudiness%20%5B%25%5D_vs_latitude.png>
:-------------------------:|:-------------------------:
<img src=WeatherPy/Images/Northern_Hemisphere-Humidity%20%5B%25%5D_vs_latitude.png>  | <img src=WeatherPy/Images/Southern_Hemisfere-Humidity%20%5B%25%5D_vs_latitude.png> 
<img src=WeatherPy/Images/Northern_Hemisphere-Temperature%20%5BF%5D_vs_latitude.png> | <img src=WeatherPy/Images/Southern_Hemisfere-Temperature%20%5BF%5D_vs_latitude.png> 
<img src=WeatherPy/Images/Northern_Hemisphere-Wind%20Speed%20%5Bmph%5D_vs_latitude.png> | <img src=WeatherPy/Images/Southern_Hemisfere-Wind%20Speed%20%5Bmph%5D_vs_latitude.png> 

##

## References
https://openweathermap.org/api - source for all weather related analysis 

https://cloud.google.com/maps-platform/places - source for maps and places
