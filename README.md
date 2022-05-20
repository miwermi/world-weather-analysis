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

With relevant weather data easily able to be grabbed in real time, development moved on to accessing google map data to generate heat maps on each climate attribute (temperature is displayed below) and then also using Google's Maps and Places API, and Search Nearby feature to collect and return hotel data for each city in our sample database. Our code asked an imaginary user to enter their ideal minimum and maximum temperatures and then returned hotels in cities with climates related to those preferences (pictured on the right below). 

<img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig13.png" width="400" height="160" alt ="graphic: Fig. 13: Heat Map"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/weather_data/Fig14.png" width="400" height="160" alt ="graphic: Fig. 14: Hotel Map in preferred climate.">

# Initial Results

It is known that our two data sources, Open Weather & Google Maps can be used to gather the very latest data on world weather and existing hotels at any time.  We can ask our users for input on their climate preferences and return hotels in cities that meet their climate preferences. We also were able to, if they requested multiple locations within one country (or driveable/walkable distance), to generate a travel itenerary map and store their trip cities. 
For our final sample, 4 cities in Indonesia were selected (we chose a very warm minimum and maximum climate in our sample, so Bali, here we come!)

<img src="https://github.com/miwermi/world-weather-analysis/blob/main/Vacation_Itenerary/WeatherPy_travel_map.png" width="400" height="160" alt ="graphic: Travel Map"> <img src="https://github.com/miwermi/world-weather-analysis/blob/main/Vacation_Itenerary//WeatherPy_travel_map_markers.png" width="400" height="160" alt ="graphic: Travel Map with City Markers.">

At this point most of the pieces of a successful application have been proven possible. Phase 1 of the project is a success. Follow up might include getting a design team working on the look of the app, a test group, and a decision making team to identify other useful things the app could do, and another coding piece might be to sort out how users might log in to asccess their map, save trips, and how much the service should cost. As additional features and details are sorted out, there is some real potential to created something users will love to use.  Planning vacations is, after all, always pretty dreamy!

# Conclusions

This app could continue to be developed and could likely contend with already existing apps if it found a niche user population via market research on user preferences in travel apps and adding features that users have found lacking in other apps of this nature. A cost benefits analysis would also need to be done to balance additional features and the development time needed to build them with the potential profitabiity of the end product. 
