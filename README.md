                                                                                           Michelle Werner (5/15/2022)
# PlanMyTrip: World Weather & Travel Mapping
---

<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/www_apis.png" width="500" height="293" alt ="graphic: World Wide Weather">
Pictured: World Wide Weather Hotel Finder & Travel App

# Project Overview
Weather data across cities worldwide was collected and analyzed via API calls to Google Maps and Open Weather Map. The client, PlanMyTrip, will use the data to recommend ideal hotels based on clients' weather preferences.

The process entailed collecting, analyzing, and visualizing the data. Code generated Pandas DataFrames with 500 or more of the world's unique cities and their weather data in real time. A collection of thumbnail images from the first portion of our analysis is displayed below. Scatter plots were used to identify trends by hemisphere, and linear regression was performed on characteristics such as minimum and maximum temperature, wind speed, cloudiness, and percent humidity.

Scatter Plots:

<img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig1.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig2.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig3.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig4.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig5.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig6.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig7.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig8.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig9.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig10.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig11.png" width="225" height="150" alt ="graphic: "> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig12.png" width="225" height="150" alt ="graphic: ">

# Analysis and App Development

Once relevant data was collected, cleaned, and the project possibilities verified, heat maps were generated for a richer user experience and work on collectng data on hotels in desireable weather locations was added to the database respository.


    Visualize Travel Data

    Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:
        Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
        Create a heatmap for the new DataFrame.
        Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
        Store the name of the first hotel in the DataFrame.
        Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

