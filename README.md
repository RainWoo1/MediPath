# MediPath

MediPath is a C++ mapping software for ambulance drivers to efficiently locate the shortest routes to hospitals and pharmacies, leveraging OpenStreetMap API, GTK, and EZGL libraries.
Implemented the A* and Multi Dijkstra algorithms to optimize pathfinding using multi-threading, incorporating real-time traffic data using the TomTom API for improved accuracy and response times.

<img src="/main_screen.png" width="300" height=auto>

## Features
Hospitals and Pharmacy Locations
Hospital and pharmacy locations are visible for users who want to find near hospitals/pharmacies. On the top left corner, users are able to toggle buttons to show the locations of hospital/pharmacy by icons. If a user clicks icons, a pop-up displays opening hours and phone numbers from the OSM database and extra API calls.


## Traffic Data
The real-time traffic data helps ambulance drivers find less traffic congested area. By enabling "Traffic Data" option from settings, the traffic data from TomTom API is rendered as Red (current speed: ~20m/s), Yellow (20m/s ~ 40m/s), and Green (40m/s ~) in the visible screen.


![Alt text](/trafficdata_demo.mov)

## Night Mode

