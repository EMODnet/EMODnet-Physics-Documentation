# EMODnet Physics WMS Service

EMODnet Physics exposes fully OGC compliant WMS service with a dedicated [GeoServer server](http://geoserver.emodnet-physics.eu/geoserver/)

It is possible to retrieve all the layers exposed by the server using the WMS GetCapabilities request:

[http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?request=getcapabilities&service=WMS](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?request=getcapabilities&service=WMS)


The definition of the EMODnet Physics parameters can be retrieved as an XML document at this link: [GetAllParameters](http://www.emodnet-physics.eu/Map/service/WSEmodnet2.aspx?q=GetAllParameters)

The definition of the EMODnet Physics parameters groups can be retrieved as an XML document at this link: [GetAllParametersGroup](http://www.emodnet-physics.eu/Map/service/WSEmodnet2.aspx?q=GetAllParametersGroup)

Live examples on how to use WMS on this page: http://www.emodnet-physics.eu/Map/service/GeoServerDefaultWMS.aspx

# Layers information

### 
Name | Description | Link 
---- | ----------- | ----
PlatformAll | All Active platforms | [GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAll/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformAll&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)

## Layers by type
Name | Description | Link 
---- | ----------- | ----
PlatformArgo |platforms of type: Argo|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformArgo/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformArgo&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformDriftBuoy |platforms of type: Drifting Buoy|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformDriftBuoy/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformDriftBuoy&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformFerrybox |platforms of type: Ferrybox|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformFerrybox/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformFerrybox&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformGlider |platforms of type: Flider|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformGlider/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformGlider&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformMooring |platforms of type: Mooring|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformMooring/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformMooring&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformOtherType |platforms of type: Other|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformOtherType/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformOtherType&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformProfiler |platforms of type: Profiler|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformProfiler/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformProfiler&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformRadar |platforms of type: HF Radar|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformRadar/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformRadar&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)

## Layers by parameter
Name | Description | Link 
---- | ----------- | ----
PlatformAtmosphere | platform with parameters group: Atmospheric |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAtmosphere/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformAtmosphere&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformChemical | platform with parameters group: Water conductivity/ BioGeoChemical |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformChemical/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformChemical&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformCurrents | platform with parameters group: Currents |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformCurrents/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformCurrents&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformLightAttenuation | platform with parameters group: Optical Properties|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformLightAttenuation/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformLightAttenuation&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformSeaLevel | platform with parameters group: Sea Level |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformSeaLevel/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformSeaLevel&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformWater | platform with parameters group: Water salinity |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWater/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformWater&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformWaterTemperature | platform with parameters group: ater Temperature |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWaterTemperature/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformWaterTemperature&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformWaves | platform with parameters group: Waves |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWaves/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformWaves&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformWind | platform with parameters group: Winds |[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformWind/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformWind&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)

## Layers by region
Name | Description | Link 
---- | ----------- | ----
PlatformArctic |platform of region: arctic/barrents/greenland/norwegian Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformArctic/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformArctic&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformAtlantic |platform of region: Atlantic/Bay of Biscay/Celtic Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAtlantic/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformAtlantic&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformBaltic |platform of region: Baltice Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformBaltic/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformBaltic&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformBlackSea |platform of region: Black Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformBlackSea/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformBlackSea&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformGlobal |platform of region: Global|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformGlobal/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformGlobal&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformMediterraneanSea |platform of region: Mediterranean Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformMediterraneanSea/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformMediterraneanSea&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
PlatformNorthSea |platform of region: North Sea|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformNorthSea/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PlatformNorthSea&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)

## Layers for Sea Level Products (data from [PSMSL](http://www.psmsl.org/) and [SONEL](http://www.sonel.org/))
Name | Description | Link | Filters ([see note](./WMS.md#note-for-sea-level-products-layers))
---- | ----------- | ---- | -------
PSMSLAnomalies |Sea level trend anomalies|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLAnomalies/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PSMSLAnomalies&styles=&bbox=-180,-90,180,90&width=768&height=330&srs=EPSG:4326&format=application/openlayers)|syear, eyear, ayear from 1900 to 2015
PSMSLSonel |Absolute Sea Level Trends|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLSonel/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PSMSLSonel&styles=&bbox=-180,-90,180,90&width=768&height=330&srs=EPSG:4326&format=application/openlayers)| yearrange from 1960 to 2013
PSMSLtrends |Global mean sea level trends since 1900|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLtrends/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PSMSLtrends&styles=&bbox=-180,-90,180,90&width=768&height=330&srs=EPSG:4326&format=application/openlayers)| year range from 1900 to 2015
PSMSL_Station |Station recorded in PSMSL database|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSL_Station/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:PSMSL_Station&styles=&bbox=-180,-90,180,90&width=768&height=330&srs=EPSG:4326&format=application/openlayers)| -

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

## Layers for Data Products (Route)
Name | Description | Link | Filters ([see note](./WMS.md#note-for-data-products-layers))
---- | ----------- | ---- | -------
route_ar_psal_60d |Platforms: Argo - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_psal_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_ar_psal_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_ar_psal_7d |Platforms: Argo - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_psal_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_ar_psal_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_ar_temp_60d |Platforms: Argo - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_temp_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_ar_temp_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_ar_temp_7d |Platforms: Argo - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_temp_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_ar_temp_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_db_atms_60d |Platforms: Drifting Buoy - Parameter: ATMS - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_atms_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_atms_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_atms_7d |Platforms: Drifting Buoy - Parameter: ATMS - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_atms_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_atms_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_dryt_60d |Platforms: Drifting Buoy - Parameter: DRYT - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_dryt_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_dryt_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_dryt_7d |Platforms: Drifting Buoy - Parameter: DRYT - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_dryt_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_dryt_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_ewct_60d |Platforms: Drifting Buoy - Parameter: EWCT - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_ewct_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_ewct_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_ewct_7d |Platforms: Drifting Buoy - Parameter: EWCT - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_ewct_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_ewct_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_psal_60d |Platforms: Drifting Buoy - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_psal_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_psal_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_psal_7d |Platforms: Drifting Buoy - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_psal_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_psal_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_temp_60d |Platforms: Drifting Buoy - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_temp_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_temp_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_db_temp_7d |Platforms: Drifting Buoy - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_db_temp_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_db_temp_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| QC
route_fb_chlt_60d |Platforms: FerryBox - Parameter: CHLT - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_chlt_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_fb_chlt_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_fb_chlt_7d |Platforms: FerryBox - Parameter: CHLT - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_chlt_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_fb_chlt_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_fb_psal_60d |Platforms: FerryBox - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_psal_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_fb_psal_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_fb_psal_7d |Platforms: FerryBox - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_psal_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_fb_psal_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_fb_temp_60d |Platforms: FerryBox - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_temp_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_fb_temp_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_fb_temp_7d |Platforms: FerryBox - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_fb_temp_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_fb_temp_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_cphl_60d |Platforms: Gliders - Parameter: CPHL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cphl_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_cphl_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_cphl_7d |Platforms: Gliders - Parameter: CPHL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cphl_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_cphl_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_cndc_60d |Platforms: Gliders - Parameter: CNDC - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cndc_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_cndc_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_cndc_7d |Platforms: Gliders - Parameter: CNDC - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_cndc_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_cndc_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_psal_60d |Platforms: Gliders - Parameter: PSAL - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_psal_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_psal_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_psal_7d |Platforms: Gliders - Parameter: PSAL - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_psal_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_psal_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_temp_60d |Platforms: Gliders - Parameter: TEMP - Time coverage: last 60 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_temp_60d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_temp_60d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC
route_gl_temp_7d |Platforms: Gliders - Parameter: TEMP - Time coverage: last 7 days|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_gl_temp_7d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_gl_temp_7d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)| Elevation - QC

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
route_mm_psal_0d |Platforms: Marine Mammals - Parameter: PSAL - Time coverage: from 2004 to 2016|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_mm_psal_0d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_mm_psal_0d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)
route_mm_temp_0d |Platforms: Marine Mammals - Parameter: TEMP - Time coverage: from 2004 to 2016|[GetCapabilities](http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_mm_temp_0d/wms?service=WMS&version=1.1.0&request=GetCapabilities&namespace=emodnet) - [Layers Preview](http://geoserver.emodnet-physics.eu/geoserver/emodnet/wms?service=WMS&version=1.1.0&request=GetMap&layers=emodnet:route_mm_temp_0d&styles=&bbox=-180,-90,180,90&width=768&height=382&srs=EPSG:4326&format=application/openlayers)

**_For information on how to use the layers for Marine Mammals Data Products please refer to [EMODnet Physics Marine Mammals Product document](EMODnetPhysicsMarineMammalsProduct.md)_**


## EXAMPLE

### OPENLAYERS 4 EXAMPLE

Platform of type: Drifting Buoy
```javascript
var layer = new ol.layer.Tile({          
	source: new ol.source.TileWMS({
	url: 'http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformAll/wms',
	params: {
		'LAYERS': 'PlatformDriftBuoy', 
		'VERSION': '1.3.0',		
        'FORMAT': 'image/png'        
		},
        serverType: 'geoserver'
	})
});
```
Data Products - Platforms: Argo - Parameter: PSAL - Time coverage: last 60 days - Elevation: near surface to 50 m - QC: 0 or 1  
```javascript
var layer = new ol.layer.Tile({          
	source: new ol.source.TileWMS({
	url: 'http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_psal_60d/wms',
	params: {
		'LAYERS': 'route_ar_psal_60d', 
		'VERSION': '1.3.0',		
		'FORMAT': 'image/png',
		'ELEVATION': '1/1',
		'CQL_FILTER': 'qc=0 OR qc=1',
		'STYLES':'refer to [Data Products Layers styling guide]',
		'ENV':'refer to [Data Products Layers styling guide]'       
		},
        serverType: 'geoserver'
	})
});
```
Sea Level Products - PSMSLtrends - year range: from 1950 to 2000
```javascript
var layer = new ol.layer.Tile({          
	source: new ol.source.TileWMS({
	url: 'http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLtrends/wms',
	params: {
		'LAYERS': 'PSMSLtrends', 
		'VERSION': '1.3.0',		
		'FORMAT': 'image/png',
		'VIEWPARAMS': 'yearrange:19502000'		   
		}
	})
});
```

### LEAFLET 1.2.0 EXAMPLE

Platform of type: Drifting Buoy
```javascript
var layer = L.tileLayer.wms(
	'http://geoserver.emodnet-physics.eu/geoserver/emodnet/PlatformDriftBuoy/wms', 
	{
		'LAYERS': 'PlatformDriftBuoy', 
		'VERSION': '1.3.0',
		'FORMAT': 'image/png' 
	});
```

Data Products - Platforms: Argo - Parameter: PSAL - Time coverage: last 60 days - Elevation: near surface to 50 m - QC: 0 or 1  
```javascript
var layer = L.tileLayer.wms(
	'http://geoserver.emodnet-physics.eu/geoserver/emodnet/route_ar_psal_60d/wms', 
	{
		'LAYERS': 'route_ar_psal_60d', 
		'VERSION': '1.3.0',
		'FORMAT': 'image/png',
		'ELEVATION': '1/1',
		'CQL_FILTER': 'qc=0 OR qc=1',
		'STYLES':'refer to [Data Products Layers styling guide]',
		'ENV':'refer to [Data Products Layers styling guide]'       		
	});
```
Sea Level Products - PSMSLtrends - year range: from 1950 to 2000
```javascript
var layer = L.tileLayer.wms(
	'http://geoserver.emodnet-physics.eu/geoserver/emodnet/PSMSLtrends/wms', 
	{
		'LAYERS': 'PSMSLtrends', 
		'VERSION': '1.3.0',
		'FORMAT': 'image/png',
		'VIEWPARAMS': 'yearrange:19502000'	
	});
```