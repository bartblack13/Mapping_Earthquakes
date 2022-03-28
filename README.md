# Mapping_Earthquakes
JavaScript, GeoJSON, Leaflet, branch creation and merging

## Purpose
The purpose of this project was to use JavaScript, Leaflet, and Mapbox to create an interactive world map that displays earthquake and tectonic plate data.  The data was obtained from online GeoJSON files. In doing this project, I learned how to do the following: 
* Working with sub-branches on GitHub:
  - Create a branch from the main branch on GitHub
  - Add, commit, and push data to a GitHub branch
  - Merge a branch with the main branch on GitHub
* Retrieve data from a GeoJSON file
* Make API requests to a server to host geographical maps
* Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
* Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
* Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
* Render maps on a local server.

## Overview
In order to achieve this, I helped two "coworkers" at Disaster Reporting Network, a mock non-profit company that specializes in disaster-related story telling, build a multilayer interactive map.  This map shows tectonic plate faultlines and the location and magnitude of the most recent earthquakes recorded in the last 7days by the USGS.  The data was retrieved via MapBox API calling.  The map consisted of 3 layers: Street view, satellite view, and a topographical view; and 3 overlays: All Recorded Earthquakes (last 7 days), Tectnoic Plate Faultlines, and Major Earthquakes (last 7 days).  Both of the earthquake overlays, used circle markers to show the location of each seismic even.  Using Javascript and Leaflet, I linked the data to the markers, so that the radius of the circle markers was directly proportional to the magnitude (larger circle = high magnitude), and each marker was color coded (low magnitude = green, high magnitude = red).  Each marker included pup-up data when clicked that included: location and magnitude.  I also included date and time of the earthquake, in the pop-up info.  To do this I parsed time stamp values from each object, then converted them from 13 digit UNIX code to date and time(with local timezone).

![This is an image]()

using knowledge of JS and d3 library, traverse and retrieve GeoJSON earthquake data and tectonic plate data, in order to populate a geographical map.
use leaflet library and the mapbox API


