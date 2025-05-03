1) Выберите из таблицы orders 3 самых дешевых заказа за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

Select * from orders
Order by SUM asc
limit 3;

2) Выберите из таблицы orders 2 самых дорогих заказов за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

Select * from orders where status != "cancelled"
Order by sum DESC
Limit 2;

3) Добавьте в таблицу orders данные о новом заказе стоимостью 8000 рублей. В заказе 4 товара (products).

Insert into orders2 (id, products, sum)
Values (6, 4, 8000);

4) Добавьте в таблицу products новый товар — «VR-очки», стоимостью 70000 рублей в количестве (count) 2 штук.

Insert into products (id, name, count, price)
Values (7, 'VR очки', 2, 70000);

5) В таблицу products внесли данные с ошибкой, вместо "PS5" в наименовании написали IMAC. Исправьте ошибку.

update products2 set name = 'PS5' where id = 7;
