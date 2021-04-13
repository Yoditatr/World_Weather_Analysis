# World_Weather_Analysis

### Project Overview

###### In this project, we are looking at different weather patterns around the global for 2000 cities and offer insights to travelers who want to book a trip along with the data to recommend ideal hotels based on clients’ weather preferences. 

###### We have three different analysis: weather database, vacation search, and vacation itinerary.

### Summary

###### - The analysis allows clients to search for locations they want to travel based on their weather preferences.

###### - Once clients have filtered the database (DataFrame) based on their temperature preferences, a heatmap will be showed to them for the maximum temperature for the filtered cities around the world.

###### - A weather description to the pop-up markers will be displayed for customers so that they know what the weather is as they are traveling.

###### - A map that shows the directions between multiple cities for customers’ travel itinerary will be displayed.

### Weather Database

###### This analysis uses Open Weather Map API to pull weather information on over 720 different cities around the world. That information consists of:

###### - Maximum Temperature
###### - Cloudiness
###### - Wind Speed
###### - Humidity
###### - Current Weather Description

###### These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination interms of weather patterns.

### Vacation Search

###### This analysis takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location.

###### The image below shows the locations of all the places in the database that have a daily temperature between 75 and 90 degrees fahrenheit.

![alt text](https://github.com/Yoditatr/World_Weather_Analysis/blob/main/WeatherPy_vacation_map.png?raw=true)

### Vacation Itinerary

###### This analysis takes the vacation search information and uses Google Maps directions API to create a vacation itinerary. 

###### The image below shows a 4 stop itinerary for cities in USA that features Ontario, Saint George, Jasper, and San Patricio.

![alt text](https://github.com/Yoditatr/World_Weather_Analysis/blob/main/WeatherPy_travel_map.png?raw=true)

###### The below image also shows the map displaying a marker layer with hotel information for the selected four cities in the US. 

![alt text](https://github.com/Yoditatr/World_Weather_Analysis/blob/main/WeatherPy_travel_map_markers.png?raw=true)
