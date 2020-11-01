# World_Weather_Analysis

## Ais
The aim of this study was to accommodate customer requests by dining hotels and destinations based on weather conditions and cities to visit.

Python allowed us to visualize the weather of almost 2000 cities around the world, using Python library, Openweather, Google API keys, we were able to create representative model of weather across world cities.

## Method: 

API call with the OpenWeatherMap.
The call were used to retrieve Latitude and Longitude,Maximum temperature, Percent humidity, Percent cloudiness, Wind speed and Weather description.

Using a piramide organization of the data analysis, we have generate new Data Frame, these were exported in .csv and used for a second analysis, we performed this same analysis for the vacation file and the it
Inputted desired temperature ranges in the Vacation_Search.ipynb from the Vacation_Search folder and based on the input temperature ranges it will filter out the destinations. The output is a google map with markers and a csv dataset that can be used for building an itinerary file..
Moreover for the Itinerary file we used the Google Maps Directions API, we used a marker layer map to generate a travel route between the 3 selected cities of choice.

## Result
With this method we get the best route to choose between the cities choose on the map.
