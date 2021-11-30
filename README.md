# Mapping_Earthquakes
Using Leaflet.js, D3.js, and GeoJSON.


# Execution:

To Create an interactive Earthquake maps 
I used a GeoJSON earthquake data from the USGS website and retrieved geographical coordinates and the magnitudes of earthquakes for the last seven days.Then adding the data to a map, including various different map styles. This interactive mapp also will allow the user to toggle the earthquake markers or tectonic plate lines on-and-off.


## Data Source:

* GeoJson file for Tectonic Plates retrieved from GitHub repository: https://github.com/fraxen/tectonicplates/tree/master/GeoJSON
* GeoJson file for Earthquakes for the past 7 days retrieved via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
* GeoJson file for Major Earthquakes (M4.5+) for the past 7 days via API call from USGS website: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

## Software:

Mapbox API static/js/challenge_logic.js
VS Code and Chrome Developer Tools
## Languages:

JavaScript,CSS,HTML

## Libraries:

D3, Leaflet



https://user-images.githubusercontent.com/85265816/144127309-c168a220-e3b1-4a14-8017-a3a74ae77fcb.mov



# Examples:

* When you load the page, it defaults to the Streets view with both the Earthquakes and Tectonic Plate overlays engaged. The legend shows you the color coding for various magnitudes.
<img width="1231" alt="image" src="https://user-images.githubusercontent.com/85265816/139952187-15ea6293-a5da-4d7f-a6e4-c7cc774c1c1a.png">


* You can select one of three different different map styles, such as the Satelite theme shown below:
<img width="1215" alt="image" src="https://user-images.githubusercontent.com/85265816/139952350-70d67427-18bd-4a87-bfd1-1dc1be33809b.png">

* You can also toggle the Earthquakes to show or not-show, as well as the Tectonic Plates.
<img width="1212" alt="image" src="https://user-images.githubusercontent.com/85265816/139952360-c6b4baad-9bf7-4e73-8c62-5bfdb7daf6d0.png">
