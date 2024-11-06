1. film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
- SELECT COUNT(film) FROM film WHERE length > ALL( SELECT AVG(film.length) FROM film  );
2. film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
- SELECT COUNT(film) FROM film WHERE rental_rate = aLL( SELECT MAX(film.rental_rate) FROM film  );
3. film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
- SELECT COUNT(film) FROM film WHERE rental_rate = aLL( SELECT MIN(film.rental_rate) FROM film) and replacement_cost = aLL( SELECT MIN(film.replacement_cost) FROM film);
4. payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
- SELECT * FROM customer WHERE customer_id = ANY (SELECT customer_id FROM payment GROUP BY customer_id ORDER BY COUNT(*) DESC LIMIT 1);
