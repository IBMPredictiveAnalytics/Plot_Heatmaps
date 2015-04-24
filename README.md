#Plot Spatial Data
###IBM SPSS Modeler Predictive Extensions

With this output node you can to plot data containing latitude and longitude on an interactive map. You can use the same color for all points or use a legend column to specify a color code. This legend may be categorical or continuous. Several color palettes are available (sequential, divergent, qualitative or monochrome) covering all possible use of the node.
More precisely, this node generates an HTML file which can be saved to a specific directory and/or opened in the default browser on execution. This html page is an interactive map, that is to say you can move, zoom in and out, etc. 

![Map](https://github.com/IBMPredictiveAnalytics/PlotGeospatialData/blob/master/Screenshot/maps.gif?raw=true)

Check some live demos here:
- [Crime in Chicago by Gender][10]

---
Requirements
----
- IBM SPSS Modeler v16.0 or later
- IBM SPSS Modeler 'R Essentials'
- R 2.15.x or R 3.1

More information here: [IBM Predictive Extensions][2]


---
Installation intructions
----
1. Download the extension: [Download][3] 
2. Close IBM SPSS Modeler. Save the .cfe file in the CDB directory, located by default on Windows in "C:\ProgramData\IBM\SPSS\Modeler\16\CDB" or under your IBM SPSS Modeler installation directory.
3. Restart IBM SPSS Modeler, the node will now appear in the Model palette.

---
R Packages used
----
The R packages will be installed the first time the node is used as long as an Internet connection is available.
- [plotGoogleMaps][4]
- [RColorBrewer][11]

---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][5] directory
- There is a sample available in the [example][6] directory

---
License
----

[Apache 2.0][1]


Contributors
----

  - Armand Ruiz ([armand_ruiz](https://twitter.com/armand_ruiz))


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]:https://developer.ibm.com/predictiveanalytics/downloads/#tab2
[3]:https://github.com/IBMPredictiveAnalytics/PlotGeospatialData/raw/master/Source%20code/plotSpatialData.cfe
[4]:http://cran.r-project.org/web/packages/plotGoogleMaps/index.html
[5]:https://github.com/IBMPredictiveAnalytics/PlotGeospatialData/blob/master/Documentation/PlotSpatialData-SPSSModelerExtension.pdf
[6]:https://github.com/IBMPredictiveAnalytics/PlotGeospatialData/tree/master/Example
[10]:http://armandruiz.com/SPSSmaps/crimeChicago1.html
[11]:http://cran.r-project.org/web/packages/RColorBrewer/index.html
