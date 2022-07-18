# sql-dev2

patika.dev linkim: https://app.patika.dev/cmilakonur <br />

1- film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 
küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.) <br />
SELECT * FROM film <br />
WHERE replacement_cost BETWEEN 12.99 AND 16.98; <br />

2- actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' <br />
değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.) <br />
SELECT first_name,Last_name FROM actor <br />
WHERE first_name IN('Penelope','Nick','Ed'); <br />

3- film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 <br />
olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.) <br />
SELECT * FROM film <br />
WHERE rental_rate IN(0.99,2.99,4.99) AND replacement_cost IN(12.99,15.99,28.99); <br />
