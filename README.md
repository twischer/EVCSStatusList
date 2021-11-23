Electric Vehicle Charging Station (EVCS) Status List
====================================================

Usage
-----
1. Register for a key at https://developer.tomtom.com/user/me/apps
1. Open https://www.google.de/maps
	1. Right-click on any EVCS
	1. Copy the Latitude and Longitude of the EVCS
1. Replace the <LAT>, <LON> and <KEY> in https://api.tomtom.com/search/2/nearbySearch/.json?lat=<LAT>&lon=<LON>&minPowerKW=1&key=<KEY>
	1. Open the URL
	1. Copy the chargingAvailability ID
1. Replace the <KEY> and <chargingAvailabilityIDs>
	https://raw.githack.com/twischer/EVCSStatusList/main/index.htm?key=[KEY]&chargingAvailability=<chargingAvailabilityIDs>
	1. Open the URL


To give it a try only replace <KEY> in
https://raw.githack.com/twischer/EVCSStatusList/main/index.htm?key=[KEY]&chargingAvailability=276009024222219

The docuementation of the used API can be found in https://developer.tomtom.com/content/search-api-explorer

