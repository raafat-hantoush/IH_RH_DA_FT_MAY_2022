![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | SQL Queries - Group By

In this lab, you will be using the [Sakila](https://dev.mysql.com/doc/sakila/en/) database of movie rentals. If you need to get the data again, refer to the official [installation link](https://dev.mysql.com/doc/sakila/en/sakila-installation.html).

The database is structured as follows:
![DB schema](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/database-sakila-schema.png)

### Instructions

1. In the table actor, what last names are not repeated? For example if you would sort the data in the table actor by last_name, you would see that there is Christian Arkoyd, Kirsten Arkoyd, and Debbie Arkoyd. These three actors have the same last name. So we do not want to include this last name in our output. Last name "Astaire" is present only one time with actor "Angelina Astaire", hence we would want this in our output list. 

Expected output:
```shell
66 rows including
ASTAIRE
BACALL
BALE
WILSON
WITHERSPOON
WRAY
```
2. Which last names appear more than once? We would use the same logic as in the previous question but this time we want to include the last names of the actors where the last name was present more than once

Expected output:
```shell
55 rows including
AKROYD
ALLEN
BAILEY
WINSLET
WOOD
ZELLWEGER
```
3. Using the rental table, find out how many rentals were processed by each employee.

Expected output:
```shell
1	8040
2	8004
```
4. Using the film table, find out how many films there are of each rating.

Expected output:
```shell
PG    194
G     178
NC-17     210
PG-13     223
R     195
```
5. What is the mean length of the film for each rating type. Round off the average lengths to two decimal places 

Expected output:
```shell
PG	  112.01
G	    111.05
NC-17	113.23
PG-13	120.44
R	    118.66
```
6. Which kind of movies (rating) have a mean duration of more than two hours?

Expected output:
```shell
PG-13
```
