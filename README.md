# Python-API-s-Challenge

# How to Run Code

1. Clone repository to folder on computer

2. Open jupyter lab

3. Navigate to Python API's HW.ipynb and run all cells



A Python script is created to visualize the weather of 500+ cities across the world of varying distance from the equator. I utilized [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

My first objective was to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


My next objective was to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

My findings were as follows:

-There is an inverse relationship between latitude and temperature
-A strong relationship was not found between humidity and latitude
-A strong relationship was not found between cloudiness and latitude
-There are not many locations in the world where wind speed reaches over 10 mph

# Screenshots

[Temp_Latitude](N_Temp_Latitude.png)


The relationship between temperature and latitude in the northern hemisphere was quantified using a scatter plot and an r-squared value.


[Wind_Latitude](S_Wind_Latitude.png)

The relationship between wind speed and latitude in the southern hemisphere was quantified using a scatter plot and an r-squared value.



