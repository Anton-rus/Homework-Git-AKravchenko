# Домашнее задание к занятию "Репликация 1" - `Антон Кравченко`
Задание 1
На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

Ответить в свободной форме.

ОТВЕТ: 

**Репликация master-slave** — это репликация с одним главным узлом (master) и несколькими подчинёнными узлами (slave). Главный узел отвечает за запись данных, а подчинённые узлы считывают данные с главного узла. Это обеспечивает высокую доступность данных и возможность масштабирования системы путём добавления новых узлов.

**Репликация master-master** — это репликация, при которой несколько главных узлов обмениваются данными между собой. Каждый главный узел может записывать и считывать данные. Такая конфигурация обеспечивает более высокую отказоустойчивость, так как в случае отказа одного из главных узлов система продолжит работать без потери данных. Однако репликация master-master сложнее в настройке и управлении, чем репликация master-slave.

Основные различия между этими двумя типами репликации:
* В конфигурации master-slave только один узел может выполнять операции записи, тогда как в конфигурации master-master несколько узлов могут одновременно выполнять операции записи.
* Репликация master-slave обычно проще в настройке и управлении.
* Репликация master-master обеспечивает более высокий уровень отказоустойчивости, но также требует более сложной настройки и управления.


Задание 2
Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.

ОТВЕТ: 

Конфигурация Docker-контейеров: 


 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/Replica1.png)

Конфигурация mysql-slave

 ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/Replica2.png)

 Конфигурация mysql-master

![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/Replica3.png) 

Создание БД world2 на master-ноде

![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/Replica5.png)

Отображение БД world2 на slave-ноде 

![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/main/lessons_screenshots/Replica6.png)
 

---
