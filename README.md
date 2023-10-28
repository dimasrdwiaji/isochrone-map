# Isochrone Map
This repository contains code for creating isochrone maps using the HERE Maps API. The code is written in Python and uses the Geopandas to create the maps.

To use the code, you will need to create a HERE Maps API account and obtain a credential.

The isochrone is made with the following parameters:
- Using car as travel mode
- Created 3 intervals of isochrone: 15, 30, and 60 minutes
- The time for the isochrone is Friday 18.30 since that's peak rush hour
- Avoid toll roads

Included in the isochrone map are additional info on the furthest achievable distance and average speed for each interval.
