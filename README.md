## What is GTFS?
A GTFS (General Transit Feed Specification), which contains static transit information, is composed of a number of text (.txt) files that are contained in a single ZIP file.  
Each file describes a particular aspect of transit information: stops, routes, trips, fares, etc.  
source: https://gtfs.org/schedule/
<hr>

#### Wien GTFS website  
https://www.data.gv.at/katalog/dataset/wiener-linien-fahrplandaten-gtfs-wien

#### SQLITE Documentation  
https://www.sqlite.org/docs.html

#### Files in this repository

# Wien GTFS Data.ipynb
Jupyter Notebook that describes processing stages of the Wien GTFS file:
1) Download  
2) Unzip  
3) Parse 
4) Create DB  
5) Create Tables  
6) Insert rows into tables  

# Wien GTFS shapes to map.ipynb
Jupyter Notebook that describes how to visualize GTFS shapes data with help of Folium package.

# wien_lines.html
Contains the html code of visualized GTFS shape table.
![screenshot](https://github.com/xngst/wien_gtfs/blob/main/Wien_shapes.jpg)

<hr>
