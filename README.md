# docker_database

This repo provides a dockerized PostGres v9.5 with the Postgis extension v2.2 based on the ubuntu trusty dist.

## Important libs 
- GEOS version 3.4.2
- PROJ4 version 4.8.0
- GDAL 1.10.1

## Usage notes
Always make sure that you have the right encoding for your database!

Run ```pg_dropcluster 9.5 main && pg_createcluster --locale en_US.UTF-8 9.5 main```

## Docker hub
You can find a build container at https://hub.docker.com/r/treckerdotcom/trecker_com_database/
