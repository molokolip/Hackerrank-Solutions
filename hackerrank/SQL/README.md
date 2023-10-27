SQL HACKERANK CHALLENGES

# 1. SELECT NAME FROM CITY WHERE COUNTRYCODE = 'USA' AND POPULATION > 120000;
---
Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.

The CITY table is described as follows:
---

#2. SELECT * FROM CITY;
---
Query all columns (attributes) for every row in the CITY table.

The CITY table is described as follows:
---

#3. SELECT * FROM CITY WHERE ID = 1661;
---
Query all columns for a city in CITY with the ID 1661.

The CITY table is described as follows:
---

#4. SELECT * FROM CITY WHERE COUNTRYCODE = "JPN";
---
Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.

The CITY table is described as follows:
---
#5. SELECT NAME FROM CITY WHERE COUNTRYCODE ="JPN";
---
Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.
The CITY table is described as follows:
---

#6. SELECT CITY, STATE FROM STATION;
---
Query a list of CITY and STATE from the STATION table.
The STATION table is described as follows:
---


# Weather Observation Station 3
---
Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

ANSWER
select distinct CITY from STATION WHERE mod(ID, 2) = 0;
---

# 7. Write a query that prints a list of employee names (i.e.: the name attribute) from the Employee table in alphabetical order.
---
select name from employee order by name;
---