Python API Project

PART 1

WeatherPY:
Background: 
Create a Python script to visualize the weather of 500+ cities across North and the Southern hemispheres.

- Randomly select at least 500 unique (non-repeat) cities based on latitude and -   longitude.
- Perform a weather check on each of the cities using a series of successive API    calls.
- Include a print log of each city as it's being processed with the city number     and city name.
- Save a CSV of all retrieved data and a PNG image for each scatter plot.

The folowing relationships were analysed using python libraries which incuded citipy.

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude


Analysis:

Maximum temperature (F) vs. Latitude:
The closer a city is to the 0 degrees latititude (Equator), the higher the max temparature. Max temparature decreases as you drift further away from the equator and especially Northwards.

Humidity (%) vs. Latitude:
Cities below the equator have a higher average humidity percentage compared to the cities north of the equator which have a generally well distributed average percentage

Cloudiness (%) vs. Latitude:
There is no significant difference in the cloudiness based on latitude.

Wind Speed (mph) vs. Latitude:
The wind speed is at a low average 4-5 mph close to the equator both sides. However the speed increases slightly as you drift away fron the equator both sides

Observation:
Southern Hemisphere climates tend to be slightly milder than those at similar latitudes in the Northern Hemisphere. This is because the Southern Hemisphere has significantly more ocean and much less land; water heats up and cools down more slowly than land.


PART 2

VacationPY

Background:
Use the weather data from weatherPY in Part 1, to plan future vacations. Use jupyter-gmaps and the Google Places API.

- Create a heat map that displays the humidity for every city from the part I.
- Narrow down the DataFrame from part 1 to find the ideal weather condition.
- Using Google Places API to find the first hotel for each city located within   5000 meters of your coordinates.
- Plot the hotels on top of the humidity heatmap with each pin containing the   Hotel Name, City, and Country.

Analysis:

Ideal weather condition:
After analysing the DataFrame, the following were the ideal weather conditions;
Cloudness = 0
Maximun average temparature + 67.5 
Average wind speed = 2.37

Heatmap:
The humidity heatmap created is accessable on this link.
https://github.com/TechnJoe/Python-API-Challenge/blob/master/Images/heatmap.png

Hotels on top of the humidity heatmap:
The hotels map is accesabble on this link.
https://github.com/TechnJoe/Python-API-Challenge/blob/master/Images/hotel_map.png












