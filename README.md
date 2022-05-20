                                                                                           Michelle Werner (5/15/2022)
# PlanMyTrip: World Weather & Travel Mapping
---

<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/www_apis.png" width="500" height="293" alt ="graphic: World Wide Weather">
Pictured: World Wide Weather Hotel Finder & Travel App

# Project Overview
Weather data across cities worldwide was collected and analyzed via API calls to Google Maps and Open Weather Map. The client, PlanMyTrip, will use the data to recommend ideal hotels based on clients' weather preferences.

The process entailed collecting, analyzing, and visualizing the data. The first code generated Pandas DataFrames with 500 or more of the world's unique cities and their weather data in real time. A collection of thumbnail images from the first portion of our analysis is displayed below. Scatter plots were used to identify trends by hemisphere, and linear regression was performed on characteristics such as minimum and maximum temperature, wind speed, cloudiness, and percent humidity.

Scatter Plots:

<img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig1.png" width="225" height="150" alt ="graphic: Fig. 1: Latitude vs Max Temp"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig2.png" width="225" height="150" alt ="graphic: Fig. 2: Latitude vs Humidity"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig3.png" width="225" height="150" alt ="graphic: Fig. 3: Latitude vs Cloudiness"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig4.png" width="225" height="150" alt ="graphic: Fig. 4: Latitude vs Wind Speed"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig5.png" width="225" height="150" alt ="graphic: Fig. 5: Linear Regression for Northern Hem. Max Temp"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig6.png" width="225" height="150" alt ="graphic: Fig. 6: Linear Regression for Southern Hem. Max Temp"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig7.png" width="225" height="150" alt ="graphic: Fig. 7: Linear Regression for Northern Hem. Humidity"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig8.png" width="225" height="150" alt ="graphic: Fig. 8: Linear Regression for Southern Hem. Humidity"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig9.png" width="225" height="150" alt ="graphic: Fig. 9: Linear Regression for Northern Hem. Cloudiness"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig10.png" width="225" height="150" alt ="graphic: Fig. 10: Linear Regression for Southern Hem. Cloudiness"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig11.png" width="225" height="150" alt ="graphic: Fig. 11: Linear Regression for Northern Hem. Wind Speed"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig12.png" width="225" height="150" alt ="graphic: Fig. 12: Linear Regression for Southern Hem. Wind Speed">

# Analysis and App Development

With relevant weather data easily able to be grabbed in real time, we moved on to using google maps to generate heat maps on each climate attribute (temperature is displayed below) and then also collecting data on hotels. Our code asked an imaginary user to enter their ideal minimum and maximum temperatures and then returned hotels only in areas with climates related to those preferences. 

<img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig13.png" width="350" height="140" alt ="graphic: Fig. 13: Heat Map"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig14.png" width="350" height="140" alt ="graphic: Fig. 14: Hotel Map in preferred climate.">



    Visualize Travel Data

    Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:
        Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
        Create a heatmap for the new DataFrame.
        Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
        Store the name of the first hotel in the DataFrame.
        Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

<img src="https://github.com/miwermi/world-weather-analysis/blob/main/Vacation_Search/WeatherPy_Vacation_Map.png" alt ="graphic: ">
