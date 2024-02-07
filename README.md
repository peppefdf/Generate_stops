# Generate_stops
Code finding closest 3 bus stops to the center of each cluster of workers.

Cluster centers are shifted to the closest worker position of each cluster to avoid pathological cases where cluster center falls in a isolated region of the map (too far from any existing stop) 

Warning: code (features.features_from_point()) seems missing some of the stops! -> to be fixed?
