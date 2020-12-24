# leaflet-challenge

From https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php got the dataset of the past 30 days in geoJson format. 

For the project, you can see there are some markers that are larger than the other markers which means that the magnitude is higer.  You can go over the marker and the popup will come up without having to click for easier viewing. 

Some of the functions that were used were `pointToLayer` and `onEachFeature`. 

Without those functions it would have been very diffcult to bind information to all the points

One great feature of using those functions was the ability bind popups to each individual point on the map.

The circle sizes corresponds to the magnitude. Two sizes were made, one for magnitudes below 5 and the other above.

A legend on the bottom right of the map shows the corresponding depth of the earthquake.

You can view the site deployed [here](https://firedynasty.github.io/homework/leaflet_challenge/). 

