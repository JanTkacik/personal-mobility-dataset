# personal-mobility-dataset
Personal mobility dataset containing 6 real people for now and 7 artificial people. 

The data for every person are data taken from android location history service. People were asked to mark places important for them as polygons on the map with historical points displayed.

For every person in real folder there are two files with following formats

Data.csv - data from android location history service

|                |      Column 1       |     Column 2      |      Column 3      |     Column 4      |
|----------------|---------------------|-------------------|--------------------|-------------------|
| Column meaning | Date-Time of point  | Latitude of point | Longitude of point | Assigned place id |
| Format         | dd:MM:yyyy HH:mm:ss | decimal degrees   | decimal degrees    | integer           |

Polygons.csv - polygons as marked by interviewed person

|                |          Column 1          |          Column 2           |     Column 3      |
|----------------|----------------------------|-----------------------------|-------------------|
| Column meaning | Latitude of boundary point | Longitude of boundary point | Assigned place id |
| Format         | decimal degrees            | decimal degrees             | integer           |


For every artificial person there is only one file

Data.csv

|                |      Column 1       |     Column 2      |
|----------------|---------------------|-------------------|
| Column meaning | Date-Time of point  | Assigned place id |
| Format         | dd:MM:yyyy HH:mm:ss | integer           |
