# Drone-Image-Position
Determining position of the image captured by a drone using it's parameters namely longitude and latitude which are extracted 
from the .srt file in which they are embedded as subtitles with their respective time stamp.
The positions extracted into the DataFrame from the .srt file are plotted using Folium library zoomed to 15 level to overview the location with a 10 pixel radius from the point of interest to ensure focus on the domain of interest.
The plotted data points not only determine the location of the drone but also help in extracting patterns regarding the flight path of the drone.

``` 
Tools used :
* Folium
* QGIS
```
<img src="https://user-images.githubusercontent.com/97392797/206224720-34ea9b09-5825-40a8-836a-db71b46e26ba.png" width="900" height="450"/>
