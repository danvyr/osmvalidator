# osmvalidator

Validation openstreetmap.org

1. Download full country pbf file.
1. Import to DB.
1. Run validation 
1. Keep OSM DB update and update the Changed_table.
    1. download new day changes pdf file
    1. parse pbf to now what nodes, ways, relations was changed
    1. Update OSM DB with osm2pgsql
    1. Run validation only for changed items
   

In future:

check all changesets for  occurrences of points in to the validation area
