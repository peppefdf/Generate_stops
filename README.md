# Generate_stops
Code finding closest bus stop to the highest density point of each cluster of workers.

Cluster centers are shifted to the closest worker position of each cluster to avoid pathological cases where cluster center falls in a isolated region of the map (too far from any existing stop) 

Warning: code [using osmnx.features.features_from_point()] seems missing most of the stops! -> to be fixed?
Much better results with GFTS files of Lurraldebus instead of osmnx?
Source of lurraldebus stops: https://gtfs.pro/en/spain
