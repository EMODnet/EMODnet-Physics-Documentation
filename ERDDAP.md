# EMODnet Physics ERDDAP Server

The EMODnet Physics ERDDAP Server is accessible at the link: http://erddap.emodnet-physics.eu/erddap/

Almost all platforms are present with LATEST (60 days) data. Soon also MONTHLY (5 years) and HISTORY data will be accessible.

## Using EMODnet Physics ERDDAP's RESTful Web Services

### Search platforms

For each platform there is one or more ERDDAP dataset.

Platforms can be searched with various parameters as QueryString parameters at the following address (return a JSON object):

http://erddap.emodnet-physics.eu/erddap/search/advanced.json

Filter type | Parameter | value
----------- |---------- | -----
Temporal resolution (LATEST, MONTHLY, HISTORY)| searchFor | EMODnetTemporalResolution=latest<br>EMODnetTemporalResolution=monthly<br>EMODnetTemporalResolution=history
LATEST NetCDF file download | searchFor | EMODnetTemporalResolution=files
Variable Name (**not usable if EMODnetTemporalResolution=files**)| variableName | variableName=[Parameter Code] ([see note](./ERDDAP.md#note-for-retrieve-parameters-code))
Bounding Box (**not usable if EMODnetTemporalResolution=files**)| MinimumLatitude<br>MinimumLongitude<br>MaximumLatitude<br>MaximumLongitude | minLat=[min latitude]<br>minLon=[min longitude]<br>maxLat=[max latitude]<br>maxLon=[max longitude]
Time (**not usable if EMODnetTemporalResolution=files**)| minTime<br>maxTime | minTime=yyyy-MM-ddTHH:mm:ssZ<br>maxTime=yyyy-MM-ddTHH:mm:ssZ

#### Note for retrieve Parameters Code
The list of Parameter Code in JSON format ca be downloaded at the address:

http://erddap.emodnet-physics.eu/erddap/categorize/variableName/index.json


### Search platforms Example

Retrieve all the platform with the following filters:
* platforms from the latest (last 60 days) datasets 
* platfroms with Sea Temperature variable (TEMP)
* platforms in the bounding Box 64,-18,41,24
* platforms with data in the time range 2017-01-01T00:00:0 - 2017-10-11T23:59:59Z

http://erddap.emodnet-physics.eu/erddap/search/advanced.json?searchFor=EMODnetTemporalResolution=latest&&variableName=temp&maxLat=64&minLon=-18&maxLon=41&minLat=24&minTime=2017-01-01T00:00:00Z&maxTime=2017-10-11T23:59:59Z

### Download data from platforms

Data can be downloaded for each platforms in various format, with personalized filters and subsettings.

**See http://erddap.emodnet-physics.eu/erddap/tabledap/documentation.html for extensive documentation**
