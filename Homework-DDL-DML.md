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

Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.




### Задание 2
Написать скрипт и настроить задачу на регулярное резервное копирование домашней директории пользователя с помощью rsync и cron.
Резервная копия должна быть полностью зеркальной
Резервная копия должна создаваться раз в день, в системном логе должна появляться запись об успешном или неуспешном выполнении операции
Резервная копия размещается локально, в директории /tmp/backup
На проверку направить файл crontab и скриншот с результатом работы утилиты.

Логи



Скрипт 

 1. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/69c15b74bfed4c28dc0ee0bc09613122ad5b4a17/lessons_screenshots/Rsync%202.2.png)

Crontab 

 1. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/69c15b74bfed4c28dc0ee0bc09613122ad5b4a17/lessons_screenshots/Rsync%202.3.png)
---
