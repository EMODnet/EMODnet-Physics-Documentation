# EMODnet Physics WFS Service

EMODnet Physics exposes fully OGC compliant EFS service with a dedicated [GeoServer server](http://geoserver.emodnet-physics.eu/geoserver/)

It is possible to retrieve all the layers exposed by the server using the WFS GetCapabilities request:

[http://geoserver.emodnet-physics.eu/geoserver/emodnet/wfs?request=getcapabilities&service=WFS](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wfs?request=getcapabilities&service=WFS)


The definition of the EMODnet Physics parameters can be retrieved as an XML document at this link: [GetAllParameters](http://www.emodnet-physics.eu/Map/service/WSEmodnet2.aspx?q=GetAllParameters)

The definition of the EMODnet Physics parameters groups can be retrieved as an XML document at this link: [GetAllParametersGroup](http://www.emodnet-physics.eu/Map/service/WSEmodnet2.aspx?q=GetAllParametersGroup)

Live examples on how to use WFS on this page: http://www.emodnet-physics.eu/Map/service/GeoServerDefaultWFS.aspx


# Layers information

### 
Name | Description | Link 
---- | ----------- | ----
PlatformAll | All Active platforms | [GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAll/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformAll&maxFeatures=50&outputFormat=application%2Fjson)

## Layers by type
Name | Description | Link 
---- | ----------- | ----
PlatformArgo |platforms of type: Argo|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformArgo/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformArgo&maxFeatures=50&outputFormat=application%2Fjson)
PlatformDriftBuoy |platforms of type: Drifting Buoy|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformDriftBuoy/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformDriftBuoy&maxFeatures=50&outputFormat=application%2Fjson)
PlatformFerrybox |platforms of type: Ferrybox|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformFerrybox/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformFerrybox&maxFeatures=50&outputFormat=application%2Fjson)
PlatformGlider |platforms of type: Flider|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformGlider/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformGlider&maxFeatures=50&outputFormat=application%2Fjson)
PlatformMooring |platforms of type: Mooring|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformMooring/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformMooring&maxFeatures=50&outputFormat=application%2Fjson)
PlatformOtherType |platforms of type: Other|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformOtherType/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformOtherType&maxFeatures=50&outputFormat=application%2Fjson)
PlatformProfiler |platforms of type: Profiler|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformProfiler/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformProfiler&maxFeatures=50&outputFormat=application%2Fjson)
PlatformRadar |platforms of type: HF Radar|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformRadar/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformRadar&maxFeatures=50&outputFormat=application%2Fjson)

## Layers by parameter
Name | Description | Link 
---- | ----------- | ----
PlatformAtmosphere | platform with parameters group: Atmospheric |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAtmosphere/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformAtmosphere&maxFeatures=50&outputFormat=application%2Fjson)
PlatformChemical | platform with parameters group: Water conductivity/ BioGeoChemical |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformChemical/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformChemical&maxFeatures=50&outputFormat=application%2Fjson)
PlatformCurrents | platform with parameters group: Currents |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformCurrents/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformCurrents&maxFeatures=50&outputFormat=application%2Fjson)
PlatformLightAttenuation | platform with parameters group: Optical Properties|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformLightAttenuation/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformLightAttenuation&maxFeatures=50&outputFormat=application%2Fjson)
PlatformSeaLevel | platform with parameters group: Sea Level |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformSeaLevel/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformSeaLevel&maxFeatures=50&outputFormat=application%2Fjson)
PlatformWater | platform with parameters group: Water salinity |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWater/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformWater&maxFeatures=50&outputFormat=application%2Fjson)
PlatformWaterTemperature | platform with parameters group: ater Temperature |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWaterTemperature/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformWaterTemperature&maxFeatures=50&outputFormat=application%2Fjson)
PlatformWaves | platform with parameters group: Waves |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWaves/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformWaves&maxFeatures=50&outputFormat=application%2Fjson)
PlatformWind | platform with parameters group: Winds |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWind/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformWind&maxFeatures=50&outputFormat=application%2Fjson)

## Layers by region
Name | Description | Link 
---- | ----------- | ----
PlatformArctic |platform of region: arctic/barrents/greenland/norwegian Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformArctic/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformArctic&maxFeatures=50&outputFormat=application%2Fjson)
PlatformAtlantic |platform of region: Atlantic/Bay of Biscay/Celtic Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAtlantic/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformAtlantic&maxFeatures=50&outputFormat=application%2Fjson)
PlatformBaltic |platform of region: Baltice Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformBaltic/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformBaltic&maxFeatures=50&outputFormat=application%2Fjson)
PlatformBlackSea |platform of region: Black Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformBlackSea/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformBlackSea&maxFeatures=50&outputFormat=application%2Fjson)
PlatformGlobal |platform of region: Global|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformGlobal/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformGlobal&maxFeatures=50&outputFormat=application%2Fjson)
PlatformMediterraneanSea |platform of region: Mediterranean Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformMediterraneanSea/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformMediterraneanSea&maxFeatures=50&outputFormat=application%2Fjson)
PlatformNorthSea |platform of region: North Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformNorthSea/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PlatformNorthSea&maxFeatures=50&outputFormat=application%2Fjson)

## Layers for Sea Level Products (data from [PSMSL](http://www.psmsl.org/) and [SONEL](http://www.sonel.org/))
Name | Description | Link | Filters ([see note](./WFS.md#note-for-sea-level-products-layers))
---- | ----------- | ---- | -------
PSMSLAnomalies |Sea level trend anomalies|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLAnomalies/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PSMSLAnomalies&maxFeatures=50&outputFormat=application%2Fjson)|syear, eyear, ayear from 1900 to 2015
PSMSLSonel |Absolute Sea Level Trends|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLSonel/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PSMSLSonel&maxFeatures=50&outputFormat=application%2Fjson)| yearrange from 1960 to 2013
PSMSLtrends |Global mean sea level trends since 1900|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLtrends/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PSMSLtrends&maxFeatures=50&outputFormat=application%2Fjson)| year range from 1900 to 2015
PSMSL_Station |Station recorded in PSMSL database|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSL_Station/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:PSMSL_Station&maxFeatures=50&outputFormat=application%2Fjson)| N.A.

### Note for Sea Level Products Layers 

The **syear**, **eyear** and **ayear** filter are used in the `viewparams` parameter of the GetMap request.  
* syear (start year) values range are from 1900 to 2015 
* eyear (end year) values range are from 1900 to 2015 
* ayear (anomaly year) values range are from 1900 to 2015 

**Constrains: syear < eyear, syear <= ayear <= eyear**

Example: `viewparams=syear:1900;eyear:2015;ayear:1900`

***

The **yearrange** filter are used in the `viewparams` parameter of the GetMap request.

The value pof the **yearrange** filter is the concatenation of the start and enbd year

Example: `viewparams=yearrange:19002015`

## Layers for Data Products
Name | Description | Link | Filters ([see note](./WFS.md#note-for-data-products-layers))
---- | ----------- | ---- | -------
route_ar_psal_60d |Platforms: Argo - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_psal_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_ar_psal_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_ar_psal_7d |Platforms: Argo - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_psal_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_ar_psal_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_ar_temp_60d |Platforms: Argo - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_temp_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_ar_temp_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_ar_temp_7d |Platforms: Argo - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_temp_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_ar_temp_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_db_atms_60d |Platforms: Drifting Buoy - Parameter: ATMS - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_atms_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_atms_60d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_atms_7d |Platforms: Drifting Buoy - Parameter: ATMS - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_atms_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_atms_7d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_dryt_60d |Platforms: Drifting Buoy - Parameter: DRYT - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_dryt_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_dryt_60d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_dryt_7d |Platforms: Drifting Buoy - Parameter: DRYT - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_dryt_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_dryt_7d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_ewct_60d |Platforms: Drifting Buoy - Parameter: EWCT - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_ewct_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_ewct_60d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_ewct_7d |Platforms: Drifting Buoy - Parameter: EWCT - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_ewct_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_ewct_7d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_psal_60d |Platforms: Drifting Buoy - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_psal_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_psal_60d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_psal_7d |Platforms: Drifting Buoy - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_psal_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_psal_7d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_temp_60d |Platforms: Drifting Buoy - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_temp_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_temp_60d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_db_temp_7d |Platforms: Drifting Buoy - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_temp_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_db_temp_7d&maxFeatures=50&outputFormat=application%2Fjson)| QC
route_fb_chlt_60d |Platforms: FerryBox - Parameter: CHLT - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_chlt_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_fb_chlt_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_fb_chlt_7d |Platforms: FerryBox - Parameter: CHLT - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_chlt_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_fb_chlt_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_fb_psal_60d |Platforms: FerryBox - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_psal_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_fb_psal_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_fb_psal_7d |Platforms: FerryBox - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_psal_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_fb_psal_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_fb_temp_60d |Platforms: FerryBox - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_temp_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_fb_temp_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_fb_temp_7d |Platforms: FerryBox - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_temp_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_fb_temp_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_cphl_60d |Platforms: Gliders - Parameter: CPHL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cphl_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_cphl_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_cphl_7d |Platforms: Gliders - Parameter: CPHL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cphl_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_cphl_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_cndc_60d |Platforms: Gliders - Parameter: CNDC - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cndc_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_cndc_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_cndc_7d |Platforms: Gliders - Parameter: CNDC - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cndc_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_cndc_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_psal_60d |Platforms: Gliders - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_psal_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_psal_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_psal_7d |Platforms: Gliders - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_psal_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_psal_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_temp_60d |Platforms: Gliders - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_temp_60d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_temp_60d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC
route_gl_temp_7d |Platforms: Gliders - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_temp_7d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_gl_temp_7d&maxFeatures=50&outputFormat=application%2Fjson)| Elevation - QC

### Note for Data Products Layers 
The **elevation** filter is used in the `elevetaion` parameter of the GetMap request.

The values for the **elevation** filter can be one of the following value:

Value | Description 
----- | -----------  
0/0   | near surface             
1/1   | near surface to 50 m
2/2   | 50 m to 100 m
3/3   | 100 m to 250 m
4/4   | 250 m to 500 m
5/5   | 500 m to 1000 m
6/6   | 1000 m to 1500 m
7/7   | 1500 m to 2000 m
8/8   | 2000 m to 2500 m
9/9   | more than 2500 m

The **QC** filter is used in the `cql_filter` parameter of the GetMap request.

The values for the **QC** filter are integer from 0 to 9 where:

Value | Description 
----- | -----------
0 | no qc performed 
1 | good data
2 | probably good data 
3 | potentially correctable bad data 
4 | bad data 
5 | value changed 
6 | Not used 
7 | nominal value 
8 | interpolated value 
9 | missing value

**For styling the Data Products layers refer to [Data Products Layers styling guide](DataProductsLayers/StylingGuide.md)**

## Layers for Marine Mammals Data Products
Name | Description | Link 
---- | ----------- | ---- 
route_mm_psal_0d |Platforms: Marine Mammals - Parameter: PSAL - Time coverage: from 2004 to 2016|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_mm_psal_0d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_mm_psal_0d&maxFeatures=50&outputFormat=application%2Fjson)
route_mm_temp_0d |Platforms: Marine Mammals - Parameter: TEMP - Time coverage: from 2004 to 2016|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_mm_temp_0d/wfs?service=WFS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [GeoJSON Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=emodnet:route_mm_temp_0d&maxFeatures=50&outputFormat=application%2Fjson)

**_For information on how to use the layers for Marine Mammals Data Products please refer to [EMODnet Physics Marine Mammals Product document](EMODnetPhysicsMarineMammalsProduct.md)_**


---

## EXAMPLE

### OPENLAYERS 4 EXAMPLE

Platform of type: Drifting Buoy
```javascript

```
#### Data Products - Platforms: Argo - Parameter: PSAL - Time coverage: last 60 days - Elevation: near surface to 50 m - QC: 0 or 1  
```javascript

```

### LEAFLET 1.2.0 EXAMPLE

Platform of type: Drifting Buoy
```javascript
var geojsonMarkerOptions = {
    'RADIUS': 4,
    'FILLCOLOR': '#ff7800',
    'COLOR': '#000',
    'WEIGHT': 1,
    'OPACITY': 1,
    'FILLOPACITY': 0.8,
};

var WFS_Parameters = {
    'SERVICE': 'WFS',
    'VERSION': '2.0.0',
    'REQUEST': 'GetFeature',
    'TYPENAME': 'emodnet:PlatformDriftBuoy',
    'OUTPUTFORMAT': 'text/javascript',
    'FORMAT_OPTIONS': 'callback:getJson',
};

var parameters = L.Util.extend(WFS_Parameters);
var URL ='http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows' + L.Util.getParamString(parameters);

var ajax = $.ajax({
    url: URL,
    dataType: 'jsonp',
    jsonpCallback: 'getJson',
    success: function (response) {
        layer = L.geoJson(response, {
            pointToLayer: function (feature, latlng) {
                return L.circleMarker(latlng, geojsonMarkerOptions);
            },
            onEachFeature: function (feature, layer) {
                layer.bindPopup("PlatformID=" + feature.properties["PlatformID"]);        
            },
        }).addTo(map);            
    }
});
```

#### Data Products - Platforms: Argo - Parameter: PSAL - Time coverage: last 60 days - Elevation: near surface to 50 m - QC: 0 or 1  
```javascript
var WFS_Parameters = {
    'SERVICE': 'WFS',
    'VERSION': '2.0.0',
    'REQUEST': 'GetFeature',
    'TYPENAME': 'emodnet:route_ar_psal_60d',
    'OUTPUTFORMAT': 'text/javascript',
    'FORMAT_OPTIONS': 'callback:getJson',       
    'ELEVATION': '1/1',
    'CQL_FILTER': 'qc=0 OR qc=1', 
    'STYLES':'refer to [Data Products Layers styling guide]',
    'ENV':'refer to [Data Products Layers styling guide]'   
    };

var parameters = L.Util.extend(WFS_Parameters);
var URL ='http://geoserver.emodnet-physics.eu/geoserver/emodnet/ows' + L.Util.getParamString(parameters);

var ajax = $.ajax({
    url: URL,
    dataType: 'jsonp',
    jsonpCallback: 'getJson',
    success: function (response) {
        layer = L.geoJson(response, {   
            style: function (feature) {
                return {
                    stroke: false,
                    fillColor: 'FFFFFF',
                    fillOpacity: 0
                };
            },             
            onEachFeature: function (feature, layer) {
                layer.bindPopup("PlatformID=" + feature.properties["PlatformID"]);        
            },
        }).addTo(map);            
    }
});
```
