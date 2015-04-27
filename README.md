#Plot Heatmaps
###IBM SPSS Modeler Predictive Extensions

This SPSS Modeler ‘output’ node allows you to plot spatial data on a density heatmap. Simply install the node, select the coordinate’s fields and choose the visual parameters that suit you best. Then start visualizing simply and easily your data directly in IBM SPSS Modeler.

![Map](https://github.com/IBMPredictiveAnalytics/Plot-Heatmaps/blob/master/Screenshot/Illustration1.png?raw=true)
![Map](https://github.com/IBMPredictiveAnalytics/Plot-Heatmaps/blob/master/Screenshot/Illustration2.png?raw=true)


Check some live screenshots here:
- [Crime in Chicago][10]

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
- [ggmap][4]
- [ggplot2][11]

---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][5] directory
- There is a sample available in the [example][6] directory
- [Video-tutorial][20]

---
License
----

[Apache 2.0][1]


Contributors
----

  - Armand Ruiz ([armand_ruiz](https://twitter.com/armand_ruiz))


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]:https://developer.ibm.com/predictiveanalytics/downloads/#tab2
[3]:https://github.com/IBMPredictiveAnalytics/Plot-Heatmaps/raw/master/Source%20code/plotHeatmaps.cfe
[4]:http://cran.r-project.org/web/packages/ggmap/index.html
[5]:https://github.com/IBMPredictiveAnalytics/Plot-Heatmaps/blob/master/Documentation/PlotHeatmap-SPSSModelerExtension.pdf
[6]:https://github.com/IBMPredictiveAnalytics/Plot-Heatmaps/tree/master/Example
[10]:https://github.com/IBMPredictiveAnalytics/Plot-Heatmaps/tree/master/Screenshot
[11]:http://cran.r-project.org/web/packages/ggplot2/index.html
[20]:https://www.youtube.com/watch?v=j1EeC4XSGdw
