# CSky2TopoCraft: QGIS DEM Downloader & Heightmap Generator
This is CSky2TopoCraft: a QGIS plugin that will allow you to automatically download, format and export realistic heightmaps to Cities Skylines 2 map editor. 


## Instructions

### Install QGIS
Download and install QGIS from https://qgis.org/en/site/forusers/download.html
### Install Plugin
![maiplugin](images/maiplugin.png)
![insfromzip](images/insfromzip.png)
### Get OpenTopography API Key
Navigate to https://opentopography.org/ and hit Request an API key to create an account.
![otrequestapikey](images/otrequestapikey.png)
Find your API key at: https://portal.opentopography.org/requestService?service=api
![otapikey](images/otapikey.png)
### Get Your Coordinates & CRS
#### Step 1
Navigate to https://mangomap.com/robertyoung/maps/69585/what-utm-zone-am-i-in-# and determine the UTM zone of your city.

![findutm](images/findutm.png)

#### Step 2
Navigate to https://epsg.io/map#srs=4326&x=0.000000&y=0.000000&z=1&layer=streets and change the CRS.

![changecrs](images/epsgchangecrs.png)
![epsgselectcrs](images/epsgselectcrs.png)

Use the map to determine the coordinates of your city.

![findcoord](images/findcoord.png)
### Using the Plugin
## Note

