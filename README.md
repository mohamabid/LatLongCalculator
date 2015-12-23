# LatLongCalculator

The 'CalculateFinerLatLongs' function in finer-latlon.js file provides the ability to calculate Latitudes and Longitudes at a given distance given a pair of Latitudes and Longitudes.

Uses:
One of the use cases where you may need finer Latitudes and Longitudes which are at a specific distance apart (Lets say 1 Meter) is to build a Driving Simulator on a Map. 
The Driving Simulator Web app I built uses the HERE Maps API. The HERE Api provides the shape points for a route from A to B. But the shape points are provided only when there is a bearing change between the start and end lat lon.
If you want to create a simulator which drives the vehicle at lets say 60 Miles per Hour, you need latitudes and longitudes which are at a specific distance so that you can create your interval in JavaScript with a specific duration in milliseconds for the interval to repeat.
Take a look at driving-simulator to see how this function was used.