![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | SQL Joins on multiple tables

In this lab, you will be using the [Sakila](https://dev.mysql.com/doc/sakila/en/) database of movie rentals.

### Instructions

1. Write a query to display for each store its store ID, city, and country.

Expected output:
```shell
1	Lethbridge	Canada
2	Woodridge	Australia
```
2. Write a query to display how much business, in dollars, each store brought in.

Expected output:
```shell
1	33489.47
2	33927.04
```
3. What is the average running time(length) of films by category?

Expected output:
```shell
Action		111.61
Animation	111.02
Children	109.80
Classics	111.67
Comedy	115.83
Documentary	108.75
Drama	120.84
Family		114.78
Foreign	121.70
Games	127.84
Horror		112.48
Music		113.65
New		111.13
Sci-Fi		108.20
Sports		128.20
Travel		113.32
```
4. Which film categories are longest(length) (find Top 5)? (Hint: You can rely on question 3 output.)

Expected output:
```shell
Sports		128.20
Games	127.84
Foreign	121.70
Drama	120.84
Comedy	115.83
```
5. Display the top 5 most frequently(number of times) rented movies in descending order.

Expected output:
```shell
BUCKET BROTHERHOOD
ROCKETEER MOTHER
FORWARD TEMPLE
GRIT CLOCKWORK
JUGGLER HARDLY
```
6. List the top five genres in gross revenue in descending order.

Expected output:
```shell
Sports		5314.21
Sci-Fi		4756.98
Animation	4656.30
Drama	4587.39
Comedy	4383.58
```
7. Is "Academy Dinosaur" available for rent from Store 1?

Expected output:
```shell
ACADEMY DINOSAUR	1
```
