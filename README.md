# Expanding Public Transportation in Bend, OR
## Final Project for Data Science in the Wild¶
*Ashley Riehl*
*March 2017*

#### Objective:
To use publicly available data to explore good opportunities for fixed-route bus expansion in Bend, Oregon.
Technologies:
* qGIS
* Python

#### Data Sources:
* Census.gov
* Deschutes County Open Data
* Natural Earth Data
* Transit Feeds
* Other

This repository contains all of the data and code necessary to:
* Geocode addresses using the Google Maps API
* Extract geocoded addresses from the resulting sqlite database
* Display basic GIS data using the geopandas package
* Create a qGIS map to visualize transit routes, various population data by census blocks, and points of interest in Bend, OR.

*Note that geocoding addresses using this code requires that a [personal API key](https://developers.google.com/maps/documentation/geocoding/start) must be entered into the geocodePersonal.py.example.py file.*
