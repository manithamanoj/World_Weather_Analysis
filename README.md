# World_Weather_Analysis
World_Weather_Analysis
## Introduction
In this project we are working for PlanMyTrip app with Jack. First, we
add the weather description to the weather data that we have already retrieved in this module. Then, we collect weather preferences from travelers and filter the data according to their weather preferences. This will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the travelers will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, to create a travel route between the four cities as well as a marker layer map.

## Analysis
 ### Retrieve Weather Data
    
 First, we generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data, we gathered in the current weather description for each city. 

<img width="1419" alt="Screen Shot 2022-02-03 at 10 53 23 PM" src="https://user-images.githubusercontent.com/72629108/152479616-bf64b8cb-a006-48bd-b4f8-95b72c2fe775.png">


### Create a Customer Travel Destinations Map
   
  With “Google maps and Places” API and travelers weather preference inputs we create a Customer Travel Destinations Map.

<img width="1263" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/72629108/152478917-b3ad9e2e-7d51-4bbc-a514-7042c3175f43.png">


### Create a Travel Itinerary Map
    
  Using the “Google Maps Directions” API, we create a travel route between the four cities as well as a marker layer map.

<img width="1263" alt="Screen Shot 2022-02-02 at 11 55 23 PM" src="https://user-images.githubusercontent.com/72629108/152479112-6c7e4c38-8bf8-42e8-ab4a-4d20b36d034b.png">


<img width="1263" alt="Screen Shot 2022-02-02 at 11 47 44 PM" src="https://user-images.githubusercontent.com/72629108/152479065-0bd64967-d5dd-4673-8b40-e95d1ea5c0bc.png">


