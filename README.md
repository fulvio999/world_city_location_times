# world city locations and time info
Coordinates (latitude, longitude) of many world city as SQL insert.

A list of many (about 10600) world city with their coordinates (latitude and longitude) and timezone info as SQL insert statements to be used in applications that need them  (eg: i have used it in a Sqlite database for Ubuntu Touch App).

As base list was used the one from by https://github.com/bahar/WorldCityLocations (Thanks).

** This version have some bug fixes about wrong city - country associations and improvements **

There are two files: 

1) world_country_city_latitude_longitude.sql ---> contains: country,city,longitude,latitude
2) city_coordinates_timezone_utc_offset.sql ---> contains: country,city,longitude,latitude,timezone,utc_offset
