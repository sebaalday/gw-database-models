# gw-database-models
This repository consists in scripts that help to manage a groundwater database and to create inputs and outputs from numerical groundwater models. 

# Hydrogeology database
This part of the website is used to create an orderly database where information is not repeated and is not lost as new wells or points are added. The database module includes pumping wells, monitoring wells, environmental wells, test pits, geotechnical wells, flow measurements, weather stations, etc. All of this types of points are assigned to a zone in the conceptual model. Each of these points can have level, chemical or flow information that change over time. 

# MODFLOW model: Input and Output

This part of the app use all the information generated below and create the inputs files to create a model in MODFLOW (maybe we can create other type of input models in differents codes). Then we have the outputs (levels, flow) to check the results (calibration, prediction). Here we can have static graphs (for reports and others) and interactive graphs (for presentations and work). 