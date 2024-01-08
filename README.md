# This repo is to have a different shape files for India. 


## Resources 

1. https://preset.io/blog/2021-02-11-superset-geodata/ 

## command for converting shape file to sql dump

ogr2ogr -nlt PROMOTE_TO_MULTI -f PGDump -t_srs "EPSG:4326" [name for the convert file eg: district.sql] [full path for shape file]