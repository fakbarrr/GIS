Background
Geospatial data is a point of knowledge about the coordinates of a map or also learn about geography that is in the earth. And I will menjelaaskan in theory what the ESRI on Geospatial retrive. In geospatial we can calculate in detail record data on file
Explanation
This is the way import shapefile data
The Python Library Shapefile (pyshp) provides read and write support for ESRI shapefile format. Shapefile format is a Geographic Information System data formats popular vectors created by ESRI. For more information about this format please read written with "ESRI Shapefile Technical Description - July 1998". Esri document describes the shp and SHX file format. Yet a third file format called dbf also required. This format is documented on the web as "Xbase File Format Specification" and a simple database-based file format created in the 1960s. Both Esri and Xbase file format is very simple in design and efficient memory which is part of the reason shapefile format remains popular despite the many ways to store and exchange GIS data available at this time.
 This documentation includes the Python 2.x-compatible libraries. A Python 3-compatible version available at the trunk pyshp Subversion project on Google Code.

This document provides examples for using pyshp to read and write shapefiles.
 When the sample census blockgroup shapefile referenced in this example is only available at google code project sites in http://code.google.com/p/pyshp. Examples of these are straight forward and you can easily run them against your own shapefile manually with minimal modification. Another example for a particular topic are constantly added to the wiki pyshp on google and blog GeospatialPython.com code.
Important: For information about map projections, shapefile, and Python please visit: http://code.google.com/p/pyshp/wiki/MapProjections
 I really hope this library eliminate worldly distractions only read and write data, and allows you to focus on the exciting and fun part of your project.
example

Before doing anything you must import the library.

>>> Import shapefiles
The examples below will use the created shapefile data from the US Census Bureau Blockgroups set up near San Francisco, CA and is available in a subversion repository pyshp google code site.
