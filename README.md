# 2.3SQLTask

Задание
Анализ данных о заказах и клиентах

У вас есть база данных для интернет-магазина, которая включает следующие таблицы:

Customers — информация о клиентах:

CustomerID (int, PK) — уникальный идентификатор клиента.

FirstName (varchar) — имя клиента.

LastName (varchar) — фамилия клиента.

Email (varchar) — адрес электронной почты клиента.

Orders — информация о заказах:

OrderID (int, PK) — уникальный идентификатор заказа.

CustomerID (int) — идентификатор клиента, совершившего заказ.

OrderDate (datetime) — дата и время создания заказа.

TotalAmount (decimal) — общая сумма заказа.

OrderDetails — информация о деталях заказов:

OrderDetailID (int, PK) — уникальный идентификатор детали заказа.

OrderID (int) — идентификатор заказа.

ProductID (int) — идентификатор продукта в заказе.

Quantity (int) — количество продуктов в заказе.

UnitPrice (decimal) — цена за единицу продукта.

Ваша задача:

Напишите SQL-запросы, которые выполняют следующие действия:

Возвращает список клиентов (имя и фамилия) с наибольшей общей суммой заказов.

Для каждого клиента из пункта 1 выводит список его заказов (номер заказа и общая сумма) в порядке убывания общей суммы заказов.

Выводит только тех клиентов, у которых общая сумма заказов превышает среднюю общую сумму заказов всех клиентов.

Важно использовать подзапросы, агрегатные функции и объединения таблиц, чтобы выполнить это задание. Оптимизируйте запрос, где это возможно.