# leaflet-challenge

From https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php retrieved the dataset of the past 30 days of earthquakes in geoJson format. 

Some of the functions that were used were `pointToLayer` and `onEachFeature`. 

Without those functions it would have been very diffcult to bind information to all the points.

The circle sizes corresponds to the magnitude. Two sizes were made, one for magnitudes below 5 and the other above.

A legend on the bottom right of the map shows the corresponding depth of the earthquake.

You can view the site deployed [here](https://firedynasty.github.io/homework/leaflet_challenge/). 

