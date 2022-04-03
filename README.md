# WeatherPy with Python APIs

## Overview of Analysis

### Deliverable 1: To randomly select 2,000 randomized latitudinal and longitudinal points and find the nearest city using the ``citipy`` module. And then make an API call to [Open Weather API](https://openweathermap.org/api) to retrieve current weather data for those cities. 

### Deliverable 2: To use aquired data from Deliverable 1 to locate the nearest cities to randomized locational points, filter said cities for temperature preferences, and then locate the nearest accomodation using [Googe Places API](https://developers.google.com/maps/documentation/places/web-service/overview). 

### Deliverable 3: To create a travel itinerary of four relatively close cities featured in Deliverable 2, displaying a potential travel route by ``driving``, ``biciclying``, or ``walking`` in a Google Map, as well as each cities weather and hotel information using [Google Directions API](https://developers.google.com/maps/documentation/directions/overview)

## Results

### Deliverable 1: Retrieving Weather Data

#### Open Weather API Data Frame

![Deliverable1](https://github.com/chrisknox97/world_weather_analysis/blob/main/additional_png/Deliverable1_df.png)

* The Python script written to create this Data Frame can be accessed [here](https://github.com/chrisknox97/world_weather_analysis/blob/main/weather_data/Weather_Database_Deliverable1.ipynb)

* A ``.csv`` file contaning this data can be accessed [here](https://github.com/chrisknox97/world_weather_analysis/blob/main/weather_data/WeatherPy_Database.csv)

### Deliverable 2: Customer Travel Destinations Map

#### Preferred Vacation Destinations Map

![Deliverable2](https://github.com/chrisknox97/world_weather_analysis/blob/main/vacation_search/WeatherPy_vacation_map.png)

* The Python script written to create this Google Map can be accessed [here](https://github.com/chrisknox97/world_weather_analysis/blob/main/vacation_search/Vacation_Search_Deliverable2.ipynb)

* A ``.csv`` file contaning this data can be accessed [here](https://github.com/chrisknox97/world_weather_analysis/blob/main/vacation_search/weatherpy_vacation.csv)

### Deliverable 3: Travel Itinerary Map

#### Travel Route Map

![Deliverable3A](https://github.com/chrisknox97/world_weather_analysis/blob/main/vacation_itinerary/WeatherPy_travel_map.png)

#### Selected Cities Data Frame

![Deliverable3B](https://github.com/chrisknox97/world_weather_analysis/blob/main/additional_png/Deliverable3_df.png)

#### Travel Area Map

![Deliverable3C](https://github.com/chrisknox97/world_weather_analysis/blob/main/vacation_itinerary/WeatherPy_travel_map_markers.png)

* The Python script written to create this Google Map can be accessed [here](https://github.com/chrisknox97/world_weather_analysis/blob/main/vacation_itinerary/Vacation_Itinerary_Deliverable3.ipynb)

## Summary

### Making API calls can be a quick and efficent method to retrieving compiled and stored cloud data in a matter of seconds. As such, it represents integral tools for data analysts for for throrough and brisk analysis, with ``Google APIs`` proving especially usualful for vidual depiction of locational data. 







