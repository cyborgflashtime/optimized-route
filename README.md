# optimized-route
A website that uses the Google Maps API to create an optimized route between up to 25 waypoints.

#### How to use: ####
1.  Go to http://dangbert.github.io/optimized-route/
2.  Enter the start location in the "waypoints" search box
3.  Enter up to 25 waypoint locations in the "Enter a waypoint" box in any order ([25 is the max the API allows](https://developers.google.com/maps/documentation/javascript/directions#waypoint-limits))
4.  Enter the end location in the "Set end location" box
5.  Mouseover a location on the left panel to view its address
6.  Delete waypoints with the red x; change start/end by entering a new location 

If the start, end, and at least one waypoint are all defined then the optimal route will be displayed on the map, and directions will be displayed in a panel to the right of the map.  You can hide/show the panel using the button in the top right of the panel.
