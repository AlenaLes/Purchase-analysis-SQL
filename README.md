# Анализ покупок пользователей с помощью SQL

## Краткое описание
Данная задача направлена на вывлод нескольких метрик по пользователям и их покупкам. Для решения использовались 2 таблицы: 
- user_actions - Содержит информацию о пользователях и их заказах
 
![image](https://github.com/AlenaLes/Purchase-analysis-SQL/assets/100629361/41841f0e-311c-4db0-9866-f806ddca1c25)

- orders - Содержит информацию о заказах

![image](https://github.com/AlenaLes/Purchase-analysis-SQL/assets/100629361/0c0339c6-22d4-4738-9df1-ffc176d90725)

- products - Содержит информацию о товарах
 
![image](https://github.com/AlenaLes/Purchase-analysis-SQL/assets/100629361/54515011-4f73-4c1f-b8cd-54cc1f970dff)
Исходные данные по таблицам не предоставляются.

Задача - Рассчитать следующие показатели:

- Общее число заказов — колонка orders_count
- Среднее количество товаров в заказе — колонка avg_order_size
- Суммарную стоимость всех покупок — колонка sum_order_value
- Среднюю стоимость заказа — колонка avg_order_value
- Минимальную стоимость заказа — колонка min_order_value
- Максимальную стоимость заказа — колонка max_order_value

Результаты:
- Создана таблица с нужными показателями

Стэк:

- SQL
- Redash

## Итоговая таблица

![image](https://github.com/AlenaLes/Purchase-analysis-SQL/assets/100629361/5dcb5b6d-0f53-4aef-8a64-e223cdf5cb16)
