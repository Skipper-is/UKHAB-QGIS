## UKHAB Styles and Geopackages

There are two style sheets available here. 

####UKHAB style from UKHAB
This style is adapted from the UKHAB released stylesheet, and additional styles from the guide
[![](https://github.com/Skipper-is/UKHAB-QGIS/blob/main/UKHAB%20Styles.png?raw=true)](https://github.com/Skipper-is/UKHAB-QGIS/blob/main/UKHAB%20Styles.png)

####UKHAB style from NE&lsquo;s BNG Calculator
This style includes the linear and point features from the BNG calculator released by Natural England.
[![](https://github.com/Skipper-is/UKHAB-QGIS/blob/main/UKHAB%20BNG.png?raw=true)](https://github.com/Skipper-is/UKHAB-QGIS/blob/main/UKHAB%20BNG.png)

#### Geopackage
This geopackage contains a number of different layers:
- Baseline layers
	- Baseline Area (With drill down list for UKHAB classes)
	- Baseline Linear (Drill down list of linear UKHAB classes) - style from NE's BNG
	- Baseline Points (For urban trees)
- Proposed layers - For mapping out your proposed development. These do not have the drill down list
	- Proposed Area (For your broad habitats of proposed development)
	- Proposed Linear
	- Proposed Point
- Red Line Boundary (for the site boundary)
- Target Notes
- Data tables

This layer can be used to digitise your habitats, and set conditions for each habitat for BNG. We use this at LC Ecological Services to map habitats for BNG, together with virtual layers (using SUM()) for the areas.
The layers have auto summing areas, and date created/updated, and author columns that auto fill.
