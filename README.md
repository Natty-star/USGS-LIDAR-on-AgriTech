# USGS-LIDAR-on-AgriTech

This project tries to build a python package for AgriTech.This project aimed to know how water flows through a maize farm field. TThis knowledge will help us improve our research on new agricultural products being tested on farms.
The purpose of this project is to build models of water flow and predict maize harvest if we better understand how water flows through a field, and which parts are likely to be flooded or too dry. 


   ## Package Installation

      pip install PDAL

      pip install geopandas

      pip install rasterio

      pip install laspy
## Description
> **LiDAR** (light detection and ranging) is a popular remote sensing mechanism used for measuring the exact distance of an object on the earth's surface. Since the introduction of GPS technology, it has become a widely used method for calculating accurate geospatial measurements. These geospatial data are used for different analysis purposes.
> **Data Featching and loading** : Fetch spacialy bound LIDAR data from user input and return python dictionary contining all years of geopandas file 

- **Terrain Visualization** : Viisualize data  and give option to show data as 
  - 3D render plot :-create 3D visualizations using a process known as volume rendering 
  - Heat map :- show data which depends on two independent variables as a color coded image plot

- **Data Transformation**
  - Topographic wetness index (TWI) - as an additional column returned with geopandas dataframe
  - Standardized grid - A python code that takes elevation points output from the USGS LIDAR tool and interpolates them to a grid.




