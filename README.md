# SQL-
SQL Homework 1
--Soru 1
SELECT title, description from film

--Soru 2
SELECT length from film;
WHERE length<75 and length>60

--Soru3
SELECT rental_rate,replacement_cost from film;
WHERE rental_rate=0.99 AND replacement_cost=12.99 OR replacement_cost=28.99

--Soru 4
SELECT first_name, last_name from customer;
WHERE first_name='Mary'

--Soru 5
SELECT length,rental_rate from film; 
WHERE length<50 AND rental_rate!=2.99 AND rental_rate!=4
