# Patikadev_PostgreSQL-1

SELECt title,description FROm film;
SELECT length FROm film WHERE length >60 and length<75;
SELECT * FROm film WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99);
SELECT last_name FROM customer WHERE first_name = 'Mary';
SELECt * FROm film
WHERE NOT length>50 AND (rental_rate = 2.99 OR rental_rate = 4.99);
