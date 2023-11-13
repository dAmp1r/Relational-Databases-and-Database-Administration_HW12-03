# Relational-Databases-and-Database-Administration_HW12-03

* SQL. Часть 1 - Горбунов Д.Н. *

Задание 1.

select distinct district  from address where district like 'K%a' and district not like '% %';

Задание 2.

select amount, payment_date from payment where amount > 10 and payment_date between '2005-06-15 00:00:00' and '2005-06-18 23:59:59';

Задание 3.

select * from rental order by rental_id desc limit 5;

Задание 4;

select active, lower (replace(last_name, 'll', 'pp')) as last_name, first_name from customer where active >= 1 and (first_name like 'Kelly' or first_name like 'Willie');
