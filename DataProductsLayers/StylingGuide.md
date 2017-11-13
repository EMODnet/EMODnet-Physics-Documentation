# Data Products Layers styling guide (Route)

The data product layers can be styled using color palette inherited from the palettes available on THREDDS Server.

The availabel palette are:

Palette name | Image | Palette name | Image | Palette name | Image | Palette name | Image
------------ | ----- | ------------ | ----- | ------------ | ----- | ------------ | -----
alg.Line.pal | ![alg.Line.pal](./palettes%20png/alg.png) | alg2.Line.pal | ![alg2.Line.pal](./palettes%20png/alg2.png) | ferret.Line.pal | ![ferret.Line.pal](./palettes%20png/ferret.png) |greyscale.Line.pal | ![greyscale.Line.pal](./palettes%20png/greyscale.png) 
ncview.Line.pal | ![ncview.Line.pal](./palettes%20png/ncview.png) | occam.Line.pal | ![occam.Line.pal](./palettes%20png/occam.png) | occam_pastel-30.Line.pal | ![occam_pastel-30.Line.pal](./palettes%20png/occam_pastel-30.png) | rainbow.Line.pal | ![rainbow.Line.pal](./palettes%20png/rainbow.png) |
redblue.Line.pal | ![redblue.Line.pal](./palettes%20png/redblue.png) | seq-blueheat.Line.pal | ![seq-blueheat.Line.pal](./palettes%20png/seq-blueheat.png) | sst_36.Line.pal | ![sst_36.Line.pal](./palettes%20png/sst_36.png) 


To generate the correct layer styling with thiese palettes we have use the GeoServer extension [Variable substitution in SLD](http://docs.geoserver.org/2.10.0/user/styling/sld/extensions/substitution.html) and
the [Interpolate Styling Transformation Functions](http://docs.geoserver.org/2.10.0/user/styling/sld/tipstricks/transformation-func.html#interpolate)

For each type of platform we have created two json file containing information about the minimum and maximum value for each parameter and the configuration of the variable sostitution.

Platform Type | Products Layers | Min/Max JSON link | Palette JSON link 
------------- | --------------- | ------------ | ------------
Argo | route_ar_psal_60d - route_ar_psal_7d <br> route_ar_temp_60d - route_ar_temp_7d <br> | [Min/Max JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_ar_MinMax.json) | [Palette JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_ar_Palette.json)
Drifting Buoy | route_db_atms_60d - route_db_atms_7d <br> route_db_dryt_60d - route_db_dryt_7d <br> route_db_ewct_60d - route_db_ewct_7d <br> route_db_psal_60d - route_db_psal_7d <br> route_db_temp_60d - route_db_temp_7d <br> | [Min/Max JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_db_MinMax.json) | [Palette JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_db_Palette.json)
Ferrybox | route_fb_chlt_60d - route_fb_chlt_7d <br> route_fb_psal_60d - route_fb_psal_7d <br> route_fb_temp_60d - route_fb_temp_7d <br> | [Min/Max JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_fb_MinMax.json) | [Palette JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_fb_Palette.json)
Gliders | route_gl_cndc_60d - route_gl_cndc_7d <br> route_gl_cphl_60d - route_gl_cphl_7d <br> route_gl_psal_60d - route_gl_psal_7d <br> route_gl_temp_60d - route_gl_temp_7d <br> | [Min/Max JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_gl_MinMax.json) | [Palette JSON](http://www.emodnet-physics.eu/Map/Products/includes/json/route_gl_Palette.json)

the Min/Max JSON is an array of ```key:value``` object where key is ```[ParamCode]_[TimeSpan]``` (e.g. "psal_7d") and value is ```[MinParamValue/MaxParamValue]``` (e.g. "18.17/39.667") like the following example:
```json
{
    ....
	"psal_7d": "18.17/39.667",
	"temp_7d": "3.16/31.251",
	"psal_60d": "10.379/39.839",
	"temp_60d": "-1.853/37.298",
    ....	
}
```
the Palette JSON is an array ```key:value``` object where key is ```[ParamCode]_[TimeSpan]``` (e.g. "psal_7d")  and value is another array ```key:value``` where key is ```[PaletteName]``` and value is the default value for the ENV parameter of the WMS GetMap request like the following example:

```json
{	
    ....
	"psal_7d": {
		"alg.Line.pal": "var:value;v0:18.17;v1:20.86;v2:23.55;v3:26.24;....",
		"alg2.Line.pal": "var:value;v0:18.17;v1:19;v2:19.83;v3:20.66;....",
		"ferret.Line.pal": "var:value;v0:18.17;v1:22.47;v2:26.77;v3:31.07;....",
		"greyscale.Line.pal": "var:value;v0:18.17;v1:39.67",
		"ncview.Line.pal": "var:value;v0:18.17;v1:18.25;v2:18.33;v3:18.41;.....",
		"occam.Line.pal": "var:value;v0:18.17;v1:18.57;v2:18.97;v3:19.37;....",
		"occam_pastel-30.Line.pal": "var:value;v0:18.17;v1:18.64;v2:19.11;....",
		"rainbow.Line.pal": "var:value;v0:18.17;v1:18.52;v2:18.87;v3:19.22;....",
		"redblue.Line.pal": "var:value;v0:18.17;v1:25.34;v2:32.51;v3:39.68",
		"seq-blueheat.Line.pal": "var:value;v0:18.17;v1:25.34;v2:32.51;v3:39.68",
		"sst_36.Line.pal": "var:value;v0:18.17;v1:18.77;v2:19.37;v3:19.97;;...."
	},		
    ...
}
```

The ENV parameter value is like "var:value;v0:value0;.....;vN:valueN" 
Where "var:value;" is a fixed string and "v0:value0;.....;vN:valueN" is a list of the value used to create the legend for the selected palette.

You can change the styling of the layer with differente min/max value creating a new value for the ENV parameters. Be sure to keep the same number of vX value

For each palette the number of possible vX is fixed. If N is the number of possible vX, the X value range if from 0 to N-1

Palette | Number of Vx
------- | ------------
alg.Line.pal | 9
alg2.Line.pal | 27
ferret.Line.pal | 6
greyscale.Line.pal | 2
ncview.Line.pal | 254
occam.Line.pal | 55
occam_pastel-30.Line.pal | 47
rainbow.Line.pal | 63
redblue.Line.pal | 4
seq-blueheat.Line.pal | 4
sst_36.Line.pal | 37

Given a minimum and maximum value for a parameter, this is a sample javascript example to create the value for the ENV parameter:

```javascript
var paletteJSONValue=[value read from the Palette JSON];
var paletteMin=0
var paletteMax=15
var numberofVx = paletteJSONValue.split(';').length - 2;
var env = "var:value";
var span = MathRound((paletteMax - paletteMin) / numberofVx, 2);
for (var i = 0; i <= numberofVx; i++)
{
    env += ";v" + i + ":" + MathRound(+paletteMin + (span * i), 2);
}
```

