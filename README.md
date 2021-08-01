# World_Weather_Analysis

## Overview

Contains 3 deliverables that interface with the OpenWeather, GoogleMaps, and GoogleDirections APIs. Outer files were completed as preperation for the deliverables.
Deliverable 3 contains an itinerary for a fun trip to Mauritius :-)

### Deliverable 1 - Retrieve Weather Data

Retrieves all of the following information from the API call:

Latitude and longitude,
Maximum temperature,
Percent humidity,
Percent cloudiness,
Wind speed,
and Weather description (for example, clouds, fog, light rain, clear sky).

Adds the weather data to a new DataFrame 

Exports the DataFrame as WeatherPy_Database.csv into the Weather_Database folder

Contains: The Weather_Database.ipynb file, 
          The WeatherPy_Database.csv file

### Deliverable 2 - Create Customer Travel Destinations Map

Input statements are written to prompt the customer for their minimum and maximum temperature preferences.

A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.

The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.

The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.

A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
Hotel name, 
City, 
Country, 
and Current weather description with the maximum temperature.

The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png.

Contains:   The Vacation_Search.ipynb file, 
            The WeatherPy_vacation.csv file, 
            The WeatherPy_vacation_map.png image
            
### Deliverable 3 - Create a Travel Itinerary Map

Four DataFrames are created, one for each city on the itinerary.

The latitude and longitude pairs for each of the four cities are retrieved.

A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png.

A DataFrame that contains the four cities on the itinerary is created.

A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information: 
Hotel name, 
City, 
Country, 
Current weather description with the maximum temperature.

Contains: The Vacation_Itinerary.ipynb file, 
          The WeatherPy_travel_map.png image, 
          The WeatherPy_travel_map_markers.png image
