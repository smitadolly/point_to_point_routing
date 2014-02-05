point_to_point_routing
======================

This repository have library for point to point routing. 


Prerequisites
1.	Install PostgreSQL - version 9.1
2.	Install PostGIS - version 1.5
3.	Install Pgrouting - version 1.05


Installation
Start pgAdmin and create a new database based on your PostGIS template. Open a Query dialog, load and execute the sql file available here. 


Attributes Requirement in the routable table are as below:
1. start_id
2. end_id
3. the_geom
4. osm_name
5. speed_in_kmh
6. length
7. reverse_length
8. row_flag (default value ‘false’)







	



