# Challenge 6, WeatherPy with Python APIs

## Project Overview
We were asked to create a city DataFrame, so that customers know the weather in the cities when they click on a pop-up marker. We also need to add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame using input statements based on the temperature range and whether or not it is raining or snowing. Finally, we need to create a directions layer Google map that shows the directions between multiple cities for travel.

The goals of this challenge are to:

1. Use nested try-except blocks.
2. Use Pandas methods and attributes on a DataFrame or Series.
3. Create a new DataFrame from a new API search with new weather parameters.
4. Filter DataFrames based on input and nested decision statements, and logical expressions.
5. Create pop-up markers on a Google map from a filtered DataFrame.
6. Add a directions layer on a Google map between cities in the filtered DataFrame.

## Resources
- Data Source: https://openweathermap.org/api
- Software: Python 3.6.1, Jupyter Notebook

# Summary
Part 1: Get the Weather Description and Amount of Precipitation for Each City, and answer to: How many cities have recorded rainfall or snow?
please run [Weather_Database.ipynb](Weather_Database.ipynb), and check [WeatherPy_challenge.csv](weather_data/WeatherPy_challenge.csv)

Part 2: Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation.
please run [Vacation_Search.ipynb](Vacation_Search.ipynb), and check the figures below for two different scenarios:

[WeatherPy_vacation_map_A.png](weather_data/WeatherPy_vacation_map_A.PNG)
[WeatherPy_vacation_map_A1.png](weather_data/WeatherPy_vacation_map_A1.PNG)
[WeatherPy_vacation_map_B.png](weather_data/WeatherPy_vacation_map_B.png)    
[WeatherPy_vacation_map_B1.png](weather_data/WeatherPy_vacation_map_B1.png)    
       
Part 3: Create a Travel Itinerary with a Corresponding Map.
please run [Vacation_Itinerary.ipynb](Vacation_Itinerary.ipynb), and check the figures below for two different scenarios:  

[WeatherPy_travel_map_A.png](weather_data/WeatherPy_travel_map_A.png) 
[WeatherPy_travel_map_B.png](weather_data/WeatherPy_travel_map_B.png) 
