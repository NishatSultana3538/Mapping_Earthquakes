# Mapping_Earthquakes

## Basic Project Plan 

### Purpose
 The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days, major earthquakes and tectonic plates.

### Tasks 
To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

### Approach 
The approach used the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I have also used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

### Resources:

Software: HTML, JavaScript, BootStrap 4.0.0
Leaflet, Mapbox.


## Results: 


Using two javascript file [challenge_logic.js](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js), one css file [style.css](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css) and [index.html](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html) file I have generated a Earthquake map where I added 3 map style from Mapbox in the base map and three geojason layer (two earthquake data sets and tectonic plate data )in the Overlay .

Below is how the Overlay map looks like with three different map style:
Street view:

![street_view](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/street_view.png)

Satellite Street view:

![Satellite_street_view](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/satellite_view.png)

Navigation Night view:

![Navigation_night](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/Navigation_night_view.png)



The map view with all earthquake data:
![all earthquake](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/all_earthquakes.png)

The map view with all earthquake data and tectonic plate data:
![all earthquake & tectonic plate](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/all%20earthqukes_tectonic%20plates.png)

The map view with tectonic plate  data:
![tectonic plate](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/tectonic-plates.png)

The map view with major earthquake & tectonic plates data:
![major earthquake_tectonic_plates](https://github.com/NishatSultana3538/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/major_earthquakes_tectonic_plates.png)




