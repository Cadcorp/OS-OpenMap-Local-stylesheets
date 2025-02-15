# OS OpenMap - Full colour style

These are QML files for OS OpenMap - Local in Geopackage format for use in QGIS.

*They have been designed to work with the data as it is supplied.*

**NOTE** that the labelling won't work in QGIS versions from 2.12 as the label engine was upgraded.

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-OpenMap-Local-stylesheets/archive/master.zip) the contents of this repository

**2.**  Copy the font file 'OSOpenMapLocal-Normal.otf' into your systems font directory (on Windows machines this is (C:\Windows\Fonts)

*Your machine may require a restart for QGIS to recognise this new font*

**3.**  Load your OS Open Map Local Geopackage data into QGIS

**4.** Roads consist of 2 layers. The road style and road labels. You will need to duplicate your Road layer once. Rename the new Road layer to RoadNames.

**5.**  Roundabouts consist of 2 layers. The roundabout casing and roundabout fill. You will need to duplicate your Roundabout layer once. Rename the original Roundabout layer and new layer to RoundaboutCase and RoundaboutFill.

**6.**  Double click on a layer to access the 'Layer Properties' window > click on 'Load Style...' > navigate to the directory containing the QML files (those ending .qml) > select the QML file that corresponds to that layer > click 'Open' > click 'OK'

*Repeat step 6 for all layers*

**7.**  Although every feature is styled, for use as a contextual map we recommend the following layer order and visibility:

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-OpenMap-Local-stylesheets/raw/master/Geopackage%20stylesheets/QGIS%20Stylesheets%20(QML)/Full%20colour%20style/images/OML_FC_layer_order.png "Recommended layer order for OS Open Map Local")

We recommend viewing the map between **1:2,500** and **1:10,000** for maximum legibility

Your map should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-OpenMap-Local-stylesheets/raw/master/Geopackage%20stylesheets/QGIS%20Stylesheets%20(QML)/Full%20colour%20style/images/OML_FC_screenshot.png "Screenshot of OS OpenMap - Local")

## Additional information

[More information about how to download, apply and customise our stylesheets including a Stylesheet User Guide](http://www.ordnancesurvey.co.uk/resources/carto-design/cartographic-stylesheets.html)

[More information about OS OpenMap - Local](http://www.ordnancesurvey.co.uk/business-and-government/products/os-open-map-local.html)

[More information about cartographic design at Ordnance Survey](https://www.ordnancesurvey.co.uk/resources/carto-design/)

## Licence

By using these stylesheets you are accepting the terms in the [Stylesheet Licence](http://www.ordnancesurvey.co.uk/docs/licences/stylesheet-licence-v2.pdf)
