# World_Weather_Analysis

## Overview of the project

This project is created to provide real-time suggestions for a travel agency clients' ideal hotels based on their preferred travel criteria via the search page.



## Results

###### Collection of the data

To collect the data I 

- Used the NumPy module to generate more than 1,500 random latitudes and longitudes.
- Used the citipy module to list the nearest city to the latitudes and longitudes.
- Used the OpenWeatherMap API to request the current weather data from each unique city in your list.
- Parsed the JSON data from the API request.
- Collected the following data from the JSON file and add it to a DataFrame:
  - City, country, and date
  - Latitude and longitude
  - Maximum temperature
  - Humidity
  - Cloudiness
  - Wind speed

###### Filtering and visualization of the data

- Filtered the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
- Found hotels from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
- Stored names of the hotels in a new DataFrame.
- Added pop-up markers to the map that display information about the city, current weather with maximum temperature, and a hotel in the city.

###### Creating a travel itinerary map

- Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. 
- Created a marker layer map with a pop-up marker for each city on the itinerary.



## Summary

This code allows clients to choose cities and hotels based on their temperature preferences and  creates a driving route  between four chosen cities. It can be easily adjusted to let clients find places based on other weather criteria and change amount of cities to visit.



