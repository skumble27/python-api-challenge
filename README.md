# python-api-challenge

##### Sumukh Kumble

### Introduction

Although it may be quite intuitive to assume that a closer proximity to the equator will no doubt witness an increase in temperature, however, this project seeks to establish a statistical relationship in support of this postulation. In order to establish these relationships, several methodologies have been applied, which have been summarised below:

​		1) Using the Python Script and the Cities Packages, over 500 cities were selected based on generating random coordinates using the Numpy module. 



​		2) These coordinates were subsequently run through the citypy module in order to determine the closest cities within these geocordinates and assign these names to a list. Specific conditions were applied in order to prevent a duplication of the cities within the list. 



​		3)  Using an API call to the Openweather database, the climatic conditions for each city within the previous list, were queried and appended to a new list containing information on geocoordinates, temperature, humidity, cloud cover and wind speed. 



Once the lists were generated, several data visualisations were undertaken and have been provided below.



### Data Visualisation

### WeathyPy



##### Latitude vs Temperature

![Lat vs Temp](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_Temperature.png)

**Figure 1: Latitude vs Temperature**

As seen in Figure 1, as the coordinates approach the latitude of zero, the maximum temperatures begin to increase, which in turn, supports the previous hypothesis that closer proximity to the equator results in high daily temperatures. 



![Latitude vs Humidity](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_Humidity.png)

**Figure 2: Latitude vs Humidity**

Although the data from Figure 1 indicates a correlation between latitude and temperatures, the humidity factor, on the other hand, appears to have a weak correlation with the latitude coordinates, suggesting that high humidity can occur through various regions on the planet. 



![Latitude vs Cloudiness](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_Cloudiness.png)

**Figure 3: Latitude vs Cloudiness.**

As seen with the humidity factor in relation to the latitudes, the same trend is apparent in determining if there is a correlation between latitudes and cloudiness. Indeed, upon visualisation of the data in Figure 3, it can be deduced that there is potentially a weak correlation between cloud cover and the coordinates of different regions suggesting that cloud cover is quite ubiquitous within the same latitude, for instance, at latitude of -20, the cloud cover varies significantly. 



![Lat vs Wind Speed](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/Latitude_vs_WindSpeed.png)



**Figure 4: Latitude vs Wind Speed**

The correlation between wind speed and latitude appears to be generally ubiquitous across the different coordinates possibly indicating that wind speeds are not confined to specific geographical locations. 



#### Comparing Climates between hemispheres

***Northern Hemisphere - Temperature (F) vs. Latitude***

![NH Temp vs Lat](https://raw.githubusercontent.com/skumble27/python-api-challenge/master/Images/NH_Latitude_vs_Max_Temp.png)

***The r-sqaured value is 0.7670***











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









