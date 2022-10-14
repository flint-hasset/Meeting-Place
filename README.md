# Meeting-Place
An implementation using OR Tools, PGeocode, and Project OSRM to identify a central meeting point, minimizing travel distances.

For the particular probem this was designed to solve, this chooses 3 centroids from an initial list of 114 potential meeting points, assigning the remaining 111 points evenly across the 3 centroids to minimize total travel time. The constraint of equally-sized end-groupings can be relaxed via paramter, as well as the number of centroids. 


