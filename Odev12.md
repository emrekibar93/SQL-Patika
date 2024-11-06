1. film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
- SELECT COUNT(film) FROM film WHERE length > ALL( SELECT AVG(film.length) FROM film  );
2. film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
- SELECT COUNT(film) FROM film WHERE rental_rate = aLL( SELECT MAX(film.rental_rate) FROM film  );
3. film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
- SELECT COUNT(film) FROM film WHERE rental_rate = aLL( SELECT MIN(film.rental_rate) FROM film) and replacement_cost = aLL( SELECT MIN(film.replacement_cost) FROM film);
4. payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
- SELECT customer.customer_id,customer.first_name,customer.last_name,COUNT(*) FROM customer INNER JOIN payment ON customer.customer_id=payment.customer_id GROUP BY customer.customer_id HAVING COUNT(*)>=(SELECT COUNT(*) FROM payment GROUP BY customer_id ORDER BY COUNT(*) DESC LIMIT 1) ORDER BY COUNT(*) DESC;
