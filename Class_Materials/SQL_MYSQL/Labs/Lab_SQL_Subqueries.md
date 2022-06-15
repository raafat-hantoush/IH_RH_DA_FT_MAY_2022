![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | SQL Subqueries

In this lab, you will be using the [Sakila](https://dev.mysql.com/doc/sakila/en/) database of movie rentals. Create appropriate joins wherever necessary. 

### Instructions

1. How many copies of the film _Hunchback Impossible_ exist in the inventory system?

Expected output:
```shell
6
```
2. List all films whose length is longer than the average of all the films.

Expected output:
```shell
489 rows including

AFFAIR PREJUDICE
AFRICAN EGG
AGENT TRUMAN
…
WRATH MILE
WRONG BEHAVIOR
YOUNG LANGUAGE
YOUTH KICK
```

3. Use subqueries to display all actors who appear in the film _Alone Trip_.

Expected output:
```shell
ED CHASE
KARL BERRY
UMA WOOD
WOODY JOLIE
SPENCER DEPP
CHRIS DEPP
LAURENCE BULLOCK
RENEE BALL
```
4. Sales have been lagging among young families, and you wish to target all family movies for a promotion. Identify all movies categorized as family films.

Expected output:
```shell
69 rows including 
AFRICAN EGG
APACHE DIVINE
ATLANTIS CAUSE
BAKED CLEOPATRA
BANG KWAI
BEDAZZLED MARRIED
BILKO ANONYMOUS
BLANKET BEVERLY

```
5. Get name and email from customers from Canada using subqueries. Do the same with joins. Note that to create a join, you will have to identify the correct tables with their primary keys and foreign keys, that will help you get the relevant information.

Expected output:
```shell
DERRICK BOURQUE	DERRICK.BOURQUE@sakilacustomer.org
DARRELL POWER	DARRELL.POWER@sakilacustomer.org
LORETTA CARPENTER	LORETTA.CARPENTER@sakilacustomer.org
CURTIS IRBY	CURTIS.IRBY@sakilacustomer.org
TROY QUIGLEY	TROY.QUIGLEY@sakilacustomer.org

```

# Optional
6. Which are films starred by the most prolific actor? Most prolific actor is defined as the actor that has acted in the most number of films. First you will have to find the most prolific actor and then use that actor_id to find the different films that he/she starred.

Expected output:
```shell
42 rows including: 
BED HIGHBALL
CALENDAR GUNFIGHT
CHAMBER ITALIAN
CHAPLIN LICENSE
CHARIOTS CONSPIRACY
CLUELESS BUCKET
COLDBLOODED DARLING
CONEHEADS SMOOCHY
DARKNESS WAR
DEER VIRGINIAN
```
7. Films rented by most profitable customer. You can use the customer table and payment table to find the most profitable customer ie the customer that has made the largest sum of payments

Expected output:
```shell
44 rows including 
DESTINY SATURDAY
CYCLONE FAMILY
SLUMS DUCK
FIDELITY DEVIL
SPLASH GUMP
MISSION ZOOLANDER
MULHOLLAND BEAST
PRINCESS GIANT
PARIS WEEKEND
RACER EGG
```
8. Customers who spent more than the average payments(this refers to the average of all amount spent per each customer).

Expected output:
```shell
285 rows including:
ALAN KAHN
ALEX GRESHAM
ALEXANDER FENNELL
…
WARREN SHERROD
WESLEY BULL
ZACHARY HITE
```
