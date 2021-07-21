## Module 13: Mapping Earthquakes Challenge

## Overview

The objective of this project is to gather earthquake data from the U.S. Geological Survey ("USGS") website and to create interactive maps of earthquakes around the world.

The earthquake data collected from the USGS contains data from earthquakes worldwide over the past week. 

This data has been extracted and loaded as a GeoJSON file, a type of JSON data specifically designed to hold geographical information. 
The final map contains the earthquake data represented as circular markers with their size and color corresponding to the magnitude of the earthquake. Each marker also has a popup that displays the magnitude and location of the earthquake. The map also contains multiple viewing layers (i.e. satellite, street) and the ability to toggle visibility of the earthquake data.  USGS

Data Source: Earthquakes GeoJSON, Earthquakes above 4.5mag GeoJSON, Tectonic Plate GeoJSON
Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0
Results
Create a Mapbox account, setup config.js and open index.html
To interact with the maps API the user have to visit mapbox.com, create a Mapbox account and retrieve the access token.
Using these APIs in combination with the Leaflet JavaScript library, enables easy and highly customizable map creation.

To access the website, please [Click Here](https://bluckoo.github.io/Module_13_Earthquakes_Challenge/).





The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

Resources


As shown below, the index.html calls for the Mapbox API key in the config.js file.



The user would have to save the token key in config.example.js and rename the file config.js:






Interactive Maps Views




