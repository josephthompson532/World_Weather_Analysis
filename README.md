# World_Weather_Analysis

## Overview
Plan My Trip is a top travel technology company tghat specializes in internet related services in the hotel and lodging industry. My job was to help collect and present data for customers via the search page which they will then filter based on their preferred travel criteria in order to find their ideal hotel anywhere in the world. To do this, we will use the citipy module to get the cities based on latitudes and longitudes and then use the OpenWeatherMap API to perform requests and get the json weather information on these cities. The analysis will help me to pick the best time of year for our users to plan their vacations. Finally we will export the data, clean it, and use the weather data to choose the best cities for vacation based on weather criteria and then map these cities using Jupyter Gmaps and the GooglePlaces API.

Step 1: 
Collect the Data

* Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
* Use the citipy module to list the nearest city to the latitudes and longitudes.
* Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
* Parse the JSON data from the API request.
* Collect the following data from the JSON file and add it to a DataFrame:
  -  City, country, and date
  -  Latitude and longitude
  -  Maximum temperature
  -  Humidity
  -  Cloudiness
  -  Wind speed
  
Step 2: 
Exploratory Analysis with Visualization

* Create scatter plots of the weather data for the following comparisons:
  - Latitude versus temperature
  - Latitude versus humidity
  - Latitude versus cloudiness
  - Latitude versus wind speed

* Determine the correlations for the following weather data:
  - Latitude and temperature
  - Latitude and humidity
  - Latitude and cloudiness
  - Latitude and wind speed

* Create a series of heatmaps using the Google Maps and Places API that showcases the following:
  - Latitude and temperature
  - Latitude and humidity
  - Latitude and cloudiness
  - Latitude and wind speed
  
Step 3:
Visualize Travel Data

* Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

 1. Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
 2. Create a heatmap for the new DataFrame.
 3. Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
 4. Store the name of the first hotel in the DataFrame.
 5. Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
 
 ## Results
 <img width="1015" alt="Screen Shot 2020-10-02 at 2 37 25 PM" src="https://user-images.githubusercontent.com/66881241/94971921-f07cb700-04bc-11eb-890b-a8f1b624bbde.png">
 
<img width="998" alt="Screen Shot 2020-10-02 at 2 37 18 PM" src="https://user-images.githubusercontent.com/66881241/94971932-f377a780-04bc-11eb-8e25-71c593a8fba7.png">

<img width="1039" alt="Screen Shot 2020-10-02 at 2 37 10 PM" src="https://user-images.githubusercontent.com/66881241/94971939-f6729800-04bc-11eb-9805-30a502b39a6f.png">
