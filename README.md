# GEO-DEV-NOTEBOOKS
Collection of ipython Notebooks focused on Geospatial Development/Data Science
Two custom Libraries in process of being constructed:
### **ArcREST_EXP_MAIN.ipynb**
Current 6-15-2021   
Library to assist in exploration of ArcREST Server and FeatureServer endpoints   
Built on top of [bmi-arcgis-restapi](https://github.com/Bolton-and-Menk-GIS/restapi) - Thanks for your efforts!
ArcREST server url is difficult to discover the location and content of layers   
ArcGIS Python API works well with a known UserID, or when items are hosted as a Feature Service   
The ArcREST Explorer creates new Classes for the Server and other data categories   
The layers or tables are able to be exported as a GeoPandas GeoDataframe for analysis and charting
### **agol_class.ipynb**
Current 6-15-2021     
Additional helper library for browsing content and extracting dataFrames from ArcGIS Online data.   
Builds on top of the [ArcGIS Python API Library](https://github.com/Esri/arcgis-python-api)   
Had previously been a collection of functions to assist in the workflow of the Python API   
Building Classes makes for easier use and no need to maintain a list of running functions   
Also allows extraction of layer/table data into a GeoPandas DataFrame   
This is conducted with a pre-constructed query via the ArcREST endpoint url   

