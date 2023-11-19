# Load Multiple Polygons GeoJSON feature collection using CSPro-JS API and Leaflet
 This is a basic example for loading multiple polygons in CSPro. Sometimes GeoJSON files coming from QGIS are not compliant with 
 the CSPro Map engines: Leaflet or Google Map. It's why, among others, I implemented the function geojsonDataString() to display GeoJSON string and test 
 them on https://geojsonlint.com/. However, even after choosen one polygon, it's mandatory to refresh the view. This could be a 
 limitation of the 7.7 CSPro-JS Api. Hopefully, we will have a more robust and fully bidirectional CSPro-JS API in the next cut.
