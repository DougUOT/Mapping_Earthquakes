# Mapping_Earthquakes
An interactive map of Earthquakes; Use JavaScript's Leaflet library along with the Mapbox API to create visualizations of earthquake data form the U.S. Geological Survey

## Overview of Project

This module will expand our JavaScript abilities and the D3 library to make an intuitive world guide. We will utilize GeoJSON; a JSON record explicitly intended to have geological data. We will explore geographical features such as points, which contain addresses and locations, like latitude and longitude coordinates. Linestrings contain facilitates for the limits of
 roads, interstates, travel courses, and structural plates. Furthermore, polygons which contain facilitate the limits of postal divisions, regions, nations, regions, and plots of land. We will likewise investigate non-spatial traits which are information free of all mathematical contemplations and bundled in the progressive design of a GeoJSON record. Utilizing our insight into JavaScript and the D3 library, we will cross and recover GeoJSON seismic tremor information and structural plate information to populate a geological guide. For this, we will likewise utilize the handout library and the Mapbox API. We should begin utilizing information from a GeoJSON record to populate a geological guide utilizing JavaScript and the D3 and pamphlet libraries

This assignment is related to the Bootcamp Data Analytics from the University of Toronto. It comprises the goals below for this module:: 

Follow below the goals for this module:

1) Objective 1: Add Tectonic Plate Data
2) Objective 2: Add Major Earthquake Data
3) Objective 3: Add an Additional Map


## Resources

* Data Source: [index.html](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html), [challenge_logic.js](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js) and [style.css](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css).
* Software & Data Tools: Visual Studio Code 1.63.2, Javascript ES6, D3 js.CSS, HTML5, Leaflet js and Chrome Browser Version 97.0.4692.71 (Official Build) (64-bit)

## Results & Code

## Objective 1: Add Tectonic Plate Data

* The tectonic plate data is added as a second layer group 
* The tectonic plate data is added to the overlay object 
* The d3.json() callback is working and does the following: 
   * The tectonic plate data is passed to the geoJSON() layer
   * The geoJSON() layer adds color and width to the tectonic plate lines
   * The tectonic layer group variable is added to the map
* The earthquake data and tectonic plate data displayed on the map when the page loads 

![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_1_1.PNG)
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_1_2.PNG)
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_1_3.PNG)

Tectonic Plate layer (Streets layer view):
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_1_4a.PNG)

Tectonic Plate and Earthquakes layer (Streets layer view):
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_1_4.PNG)

## Objective 2: Add Major Earthquake Data

* The major earthquake data is added as a third layer group 
* The major earthquake data is added to the overlay object 
* The d3.json() callback is working and does the following: (
   * Sets the color and diameter of each earthquake.
   * The major earthquake data is passed to the geoJSON() layer.
   * The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
   * The major earthquake layer group variable is added to the map
* All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off 

![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_2_1.PNG)
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_2_2.PNG)
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_2_3.PNG)
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_2_4.PNG)

Tectonic Plate, Earthquakes and major Earthquakes layer (Satellite layer view):
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_2_5.PNG)

## Objective 3: Add an Additional Map

* Create a third map tile layer and add to the overlay object
* Display all the earthquake data and tectonic plate data on the all maps of the webpage

![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_3_1.PNG)

Tectonic Plate, Earthquakes and major Earthquakes layer with marker and information such as Magnitude and Location (Dark layer view):
![](https://github.com/DougUOT/Mapping_Earthquakes/blob/main/Resources/Images/Capture13_3_2.PNG)

