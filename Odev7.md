1. film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.
- SELECT rating FROM film GROUP BY rating;
2. film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.
- SELECT rating, COUNT(rating) FROM film GROUP BY rating HAVING COUNT(rating)>50;
3. customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir?
- SELECT store_id, COUNT(store_id) FROM customer GROUP BY store_id
4. city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.
- SELECT country_id, COUNT(country_id)  FROM city GROUP BY country_id ORDER BY COUNT(country_id) DESC LIMIT 1; 
