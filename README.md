# patika.dev---sql---odev4
https://app.patika.dev/cataldirect

1 - film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.

CEVAP:

    SELECT DISTINCT replacement_cost FROM film
    
2 - film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?

CEVAP: 

    SELECT COUNT (DISTINCT replacement_cost) FROM film
    
    
3 - film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?

CEVAP:

    SELECT COUNT(title) FROM film WHERE title LIKE 'T%' and rating ='G'
    
4 - country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?

CEVAP:

    SELECT COUNT(country) FROM country WHERE country LIKE '_____'
    
5 - city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?

CEVAP:

    SELECT * FROM city WHERE city LIKE '%r' or city LIKE '%R'
