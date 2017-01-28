
Background
This data consists of observations kno coordinate point of view the real world. Spatial data consists of observations with lokasii. Spatial data to identify features and position on the surface bumii. All tellah GIS software designed to handle spatial data and to simplify.
1. What is retrive?
2. What is the SHP?
3. What's included in the SHP?
4. How is the data retrieval operation on Phython?
Geospatial data retrive is one way to retrieve the geometry data and database geospatial data from SHP file.
Shapfile or SHP is the data that stores geometric data in it, namely:
1. Bbox is a view in the map coordinates of the boundary and generally rectangular in shape on the map, BBOX is a boundary box is the coordinate point 4.
2. Shape Type there are three types, namely:
· Point: coordinates of points (1 point / coordinates) standard bernomerkan 1 of ESRI.
· Polyline: coordinates of the points that make up the line but does not establish a standard bernomerkan area 3 of ESRII.
· Polygon: coordinate establish standard bernomerkan area 5 of ESRI.
Data retrieval operations in Python
How to read the amount of data Geometry:
- Import shapefile
- Sf = shapefile.Reader ( "namafile.shp")
- Sf.shapes ()
- A = sf.shapes ()
- Len (a)
How to read the amount of data Geometry:
- Import shapefile
- Sf.records ()
- Sf.records (n)
Cover
Conclusion
Geospatial data retrive is one way to retrieve the geometry data and database geospatial data from SHP file, where the data is the data vector which is one type of geospatial data.
Suggestion
Advice from me continue to learn Retrieve geospatial data more deeply, so that we know better and do lab work independently
