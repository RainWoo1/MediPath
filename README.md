# MediPath

MediPath is a C++ mapping software for ambulance drivers to efficiently locate the shortest routes to hospitals and pharmacies, leveraging OpenStreetMap API, GTK, and EZGL libraries.
Implemented the A* and Multi Dijkstra algorithms to optimize pathfinding using multi-threading, incorporating real-time traffic data using the TomTom API for improved accuracy and response times.

[Check out our prototype using Figma!](https://www.figma.com/design/qTqsYCIitYf9UeCHXm1Det/ECE297-Design-Components?node-id=0-1&t=14Bk0oDsFigu4K3j-1)

<p align=center>
  <img src="/main_screen.png" width="800" height=auto align="center">
</p>

## Features
### Hospitals and Pharmacy Locations
Hospital and pharmacy locations are visible for users who want to find near hospitals/pharmacies. On the top left corner, users are able to toggle buttons to show the locations of hospital/pharmacy by icons. If a user clicks icons, a pop-up displays opening hours and phone numbers from the OSM database and extra API calls.

### Traffic Data
The real-time traffic data helps ambulance drivers find less traffic congested area. By enabling "Traffic Data" option from settings, the traffic data from TomTom API is rendered as Red (current speed: ~20m/s), Yellow (20m/s ~ 40m/s), and Green (40m/s ~) in the visible screen.

<p align=center>
  <img src="/trafficdata.png" width="800" height=auto>
</p>

### Night Mode

### Searching
A user has two options to find a path.
1. Using the navigation panel
If the user types intersections/street names in the search bars and clicks ‘Navigate’ or Enter, the resulting navigation path is highlighted on the map. A left panel shows the travel time and direction with guidelines.

<img src="/searching1.png" width="400" height=auto>
<img src="/searching2.png" width="400" height=auto>
<img src="/searching3.png" width="400" height=auto>
<img src="/searching4.png" width="400" height=auto>

2. Through direct selection on the map
By clicking intersections on the map, the displayed route
<img src="/searching5.png" width="400" height=auto>
<img src="/searching6.png" width="400" height=auto>



