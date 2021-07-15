# Patika_SQL_Egitimi_Odev2
1. Soru: film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla
sıralayınız ( BETWEEN - AND yapısını kullanınız.)
+ ` SELECT * FROM film WHERE replacement_cost BETWEEN 12.99 AND 16.99 `
2. Soru: actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması
koşuluyla sıralayınız. ( IN operatörünü kullanınız.)
+ ` SELECT first_name, last_name FROM actor where first_name in ('Penelope','Nick','Ed')`
3. Soru: film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız.
+ ` select * from film where rental_rate in (0.99,2.99,4.99) and replacement_cost in (12.99,15.99,28.99)`

