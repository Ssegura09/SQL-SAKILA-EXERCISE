# SQL-SAKILA-EXERCISE
SELECT * FROM actor WHERE first_name = 'John';
SELECT * FROM actor WHERE last_name = 'Neeson';
SELECT * FROM actor WHERE mod(actor_id, 10) = 0;
SELECT * FROM film WHERE film_id = 100;
SELECT * FROM film WHERE rating = 'R';
SELECT * FROM film WHERE rating != 'R';
SELECT * FROM film ORDER BY length ASC LIMIT 10;
SELECT * FROM film WHERE special_features LIKE '%deleted scenes%'; 
SELECT * FROM film_category WHERE category_id = 11;

