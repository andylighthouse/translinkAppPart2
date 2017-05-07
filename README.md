# translinkAppPart2

I wrote the following functionalities:

showing all the stops on the map and in clusters if stops are too close together
  - markStops method in the MapDisplayFragment.java file in the ui folder
 
tracking nearest stop and out of range
  - handleLocationChange method in the MapDisplayFragment.java file in the ui folder
  - updateMarkerOfNearest method in the MapDisplayFragment.java file in the ui folder
  - onLocationChanged method in the BusesAreUs.java file in the util folder
  
map the routes on the map when a stop is clicked
  - plotRoutes method in the MapDisplayFragment.java file in the ui folder
  - onStopSelected method in in the BusesAreUs.java file in the util folder
  
implmenting HttpArrivalDataProvider
  - the code in the HttpArrivalDataProvider.java file in the providers folder
  
get the arrival information
  - getArrivalsForSelectedStop method in the ArrivalsListFragment.java file in the ui folder
