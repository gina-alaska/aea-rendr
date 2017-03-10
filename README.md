# aea-rendr
Repo for Alaska Energy Authority (AEA)] - Renewable Energy Development Regions dataset.

This is a project to help track the latest copy of the AEA Renewable Energy Development Regions.

Renewable Energy Development Regions are geographic regions as defined by the AEA that represent
areas of Alaska with relatively similar energy characteristics.

These boundaries generally follow the regional boundaries established by the
Alaska Native Claims Settlement Act of 1971 (ANCSA), with the exception of where
there are electrical interconnections which cross ANCSA boundaries.

This geospatial dataset was obtained by UAF-GINA as a sub-component of the 2015
Renewable Energy Atlas of Alaska GIS data delivery.

These Renewable Energy Developement Regions appear in the web-map verison of the
Renewable Energy Atlas of Alaska which is hosted on the [AEA - Alaska Energy Data
Inventory website](http://akenergyinventory.org). These data are also used by
the UAA-ISER - [Alaska Energy Data Gateway website](http://akenergygateway.alaska.edu)
as a Data Search filter.

UAF-GINA and UAA-ISER recognize the benefit of standardizing this data layer to
ensure that both the Alaska Energy Data Inventory (AEDI) and the Alaska Energy
Data Gateway (AEDG) websites remain consistent, and that data referenced by each
site remains synchronized.

Furthermore, AEA is now contemplating the likely need to update or sub-divide
these region boundaries in response to the growth of energy infrastructure in
Alaska that has taken place over the past several decades.

This github repo has been generated as a place where AEA, UAF-GINA and UAA-
ISER can collaborate and synchronize changes, both proposed and final, during
the process of updating the Renewable Energy Development Regions of Alaska
dataset.

Version 2015 (base dataset obtained from AEA) prior to any updates:
- The primary version is shapefile shp/aea_renewable_energy_development_regions_2015.shp.zip
-- Note that the srs is EPSG:3338
- There is also a geojson version geojson/renewable_energy_development_regions_4326.geojson
-- Note the srs of the geojson is EPSG:4326 so that it displays in the github mapbox viewer

File used to seed the AEA Energy Regions database table in the Alaska Energy Data Gateway
(obtained from UAA-ISER)
- csv/aea_energy_regions_from_energy_statistics.csv

The data and documentation here is under the [Creative Commons CC-BY-SA]
(https://creativecommons.org/licenses/by-sa/4.0/) license.
