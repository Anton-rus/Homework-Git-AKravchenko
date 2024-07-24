# Домашнее задание к занятию "Работа с данными (DDL/DML)" - `Антон Кравченко`


### Инструкция по выполнению домашнего задания

### Задание 1

1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp.

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

Скриншот: 

 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/DDL%2CDML%201.3.png)

1.4. Дайте все права для пользователя sys_temp.

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

Скриншот:
 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/DDL%2CDML%201.5.png)
1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос:

ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

Скриншот: 
 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/DDL%2CDML%201.8.png)

Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.

Все запросы: 

 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/DDL%2CDML%20All%20commands.png)
 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/DDL%2C%20DML%20All%20commands%202.png)


### Задание 2
Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)

Название таблицы | Название первичного ключа
customer         | customer_id

 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/DDL%2CDML%202%20new.png)

---
