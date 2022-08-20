# Mapping_Earthquakes
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. To complete this project, I used a URL for GeoJSON earthquake data from the USGS website and retrieved geographical coordinates and the magnitudes of the most recent earthquakes then added the data to a map. I was able to use the JavaScript and the D3.js library to retrieve the coordinates and msnitudes of the earthquakes from the GeoJSON data. The Leaflet library was used to plot the data on to a Mapbox mpa through an API request and then to create an interactive interface for the data. Once the map with the basic data was created, I was then able to show the earthquake information in relation to the tectonic plates' locations on the earth. Major earthquakes with a magnitude greater than 4.5 and also able to be shown on their own overlay.

## The Layout
Upon loading, the map is centered over the US, but you can move to any part of the world. 
Here is a street overlay shot from part of the "Ring of fire", which is a path along the Pacific Ocean characterized by active volcanoes and frequent earthquakes

![demo shot](https://user-images.githubusercontent.com/19378130/185759588-b0242e81-2c83-418d-9a38-502f1c7618c2.PNG)

There are a total of four different map overlays, and three map layers.

![legend](https://user-images.githubusercontent.com/19378130/185759855-abb323cf-88da-4818-b573-92ceef13fcb3.png)


The overlays include:
- Streets
- Satellite
- Outdoors
- Dark

(dark overlay with earthquake map)

![dark](https://user-images.githubusercontent.com/19378130/185759701-a4fbb973-25c7-45c2-b3a2-35063dc81e26.PNG)

(outdoor overlay with earthquake map)

![outdoors](https://user-images.githubusercontent.com/19378130/185759707-e81a8b4e-2de8-459b-9a3e-09e7b830bdc5.PNG) 



The three map types include:
- Earthquakes
- Tectonic Plates
- Major Earthquakes

(tectonic plates map on dark overlay)

![tectonic plates](https://user-images.githubusercontent.com/19378130/185759774-cf550ca2-4140-4fbe-919b-7fa99ee6c730.PNG)

(major earthquakes map on satellite overlay)

![major quakes](https://user-images.githubusercontent.com/19378130/185759798-3fe8ff0a-a03d-4bb9-9a04-62efdb49019b.PNG)


## What does the data show?
All of this data was taken from 8/20/2022. We can see that nearly all of the earthquakes took place along the tectonic plates. It's interesting to see all the lower magnitude earthquakes reported in North America, but the other continents seem to have almost none. It brings up the question of if the smaller earthquakes are being felt or recorded at all. This data really brings to light just how often eartquakes happen.



