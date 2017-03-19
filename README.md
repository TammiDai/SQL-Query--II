# SQL-Query--II
Query the list of CITY names starting with vowels (i.e., a, e, i, o, or u) from STATION. Your result cannot contain duplicates.

station table
ID     num
City   varchar(21)
State  varchar(2)
Lat_N  num
Long_W  num



SELECT distinct city FROM station
WHERE substring(city,1,1) like '[aeiou]%'; 
