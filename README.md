# python-api-challenge

##### Sumukh Kumble

### Introduction

Although it may be quite intuitive to assume that a closer proximity to the equator will no doubt witness an increase in temperature, however, this project seeks to establish a statistical relationship in support of this postulation. In order to establish these relationships, several methodologies have been applied, which have been summarised below:

​		1) Using the Python Script and the Cities Packages, over 500 cities were selected based on generating random coordinates using the Numpy module. 



​		2) These coordinates were subsequently run through the citypy module in order to determine the closest cities within these geocordinates and assign these names to a list. Specific conditions were applied in order to prevent a duplication of the cities within the list. 



​		3)  Using an API call to the Openweather database, the climatic conditions for each city within the previous list, were queried and appended to a new list containing information on geocoordinates, temperature, humidity, cloud cover and wind speed. 



Once the lists were generated, several data visualisations were undertaken and have been provided below.



### Data Summary

#### WeatherPy

From the analyses of the weather patterns across over 500 randomly selected cities, it appears that there is indeed a strong correlation between proximity to the equator and an increase in daily maximum temperature, however this correlation is not evident when analysing other factors such as cloud cover, wind speed and humidity (Table 1). The linear regression analyses that were undertaken to further assess correlations between wind speed, humidity and cloud cover within the northern hemisphere indicate a weak correlation suggesting that the three weather factors can occur across different geographical locations as opposed to daily maximum temperatures. 



**Table 1: Climate comparisons across different regions**

| Regions                                             | r-squared value | Correlation |
| --------------------------------------------------- | --------------- | ----------- |
| Northern Hemisphere - Temperature (F) vs. Latitude  | 0.757           | strong      |
| Southern Hemisphere - Temperature (F) vs. Latitude  | 0.497           | modest      |
| Northern Hemisphere - Humidity (%) vs. Latitude     | 0.028           | weak        |
| Southern Hemisphere - Humidity (%) vs. Latitude     | 0.012           | weak        |
| Northern Hemisphere - Cloudiness (%) vs. Latitude   | 0.023           | weak        |
| Southern Hemisphere - Cloudiness (%) vs. Latitude   | 0.002           | weak        |
| Northern Hemisphere - Wind Speed (mph) vs. Latitude | 0.010           | weak        |
| Southern Hemisphere - Wind Speed (mph) vs. Latitude | 0.027           | weak        |





### Data Visualisation



##### Latitude vs Temperature

![Lat vs Temp](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_Temperature.png)

**Figure 1: Latitude vs Temperature**



![Latitude vs Humidity](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_Humidity.png)

**Figure 2: Latitude vs Humidity**



![Latitude vs Cloudiness](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_Cloudiness.png)

**Figure 3: Latitude vs Cloudiness.**



![Lat vs Wind Speed](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_WindSpeed.png)



**Figure 4: Latitude vs Wind Speed**



#### Comparing Climates between hemispheres

***Northern Hemisphere - Temperature (F) vs. Latitude***

![NH Temp vs Lat](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/NH_Latitude_vs_Max_Temp.png)

***Southern Hemisphere - Temperature (F) vs. Latitude***

![SH Temp vs Lat](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/sh_Latitude_vs_Max_Temp.png)



***Northern Hemisphere - Humidity (%) vs. Latitude***

![NH Humidity](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/NH_Latitude_vs_Humidity.png)

***Southern Hemisphere - Humidity (%) vs. Latitude***

![SH Humidity](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/sh_Latitude_vs_Humidity.png)

***Northern Hemisphere - Cloudiness (%) vs. Latitude***

![Nh Cloudiness](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/NH_Latitude_vs_cloudiness.png)



***Southern Hemisphere - Cloudiness (%) vs. Latitude***

![SH Cloudiness](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/sh_Latitude_vs_cloudiness.png)

***Northern Hemisphere - Wind Speed (mph) vs. Latitude***

![WindSpeed](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/NH_Latitude_vs_windspeed.png)



***Southern Hemisphere - Wind Speed (mph) vs. Latitude***

![SH Wind Speed](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/sh_Latitude_vs_windspeed.png)

