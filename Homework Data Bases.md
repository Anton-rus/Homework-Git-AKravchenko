### Задание 1. Кеширование
Задание 1
Опишите не менее семи таблиц, из которых состоит база данных:

какие данные хранятся в этих таблицах;
какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.


### Ответ 1. 
1. Сотрудники (
- id сотрудника первичный ключ, serial 
- ФИО сотрудника, varchar(50))
- Дата найма, date 
- id должности внешний ключ, integer
- id структурного подразделения, внешний ключ, integer
- id филиала, внешний ключ, serial 
- Оклад decimal (10,2)) 

2. Филиалы ( 
- id филиала первичный ключ, serial
- Город, varchar(20) 
- Адрес, varchar(50))
3. Должности (
- id должности, первичный ключ, serial 
- Название должности, varchar(50)) 
4. Типы подразделений (
- id типа подразделения, первичный ключ, serial,
- тип подразделения varchar(15))
5. Структурные подразделения (
- id структурного подразделения, первичный ключ, serial 
- структурное подразделение varchar(100)
- id типа подразделения, внешний ключ, serial 
- id филиала, внешний ключ serial
6.	Проекты (
- id проекта, первичный ключ, serial,
- название проекта varchar(50))
7.	Назначения на проекты (
-	id сотрудника, внешний ключ, integer,
-	id проекта, внешний ключ, integer,)
 
