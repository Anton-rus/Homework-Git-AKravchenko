# Домашнее задание к занятию "`Disaster recovery и Keepalived`" - `Антон Кравченко`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   


---

### Задание 1

Дана схема для Cisco Packet Tracer, рассматриваемая в лекции.
На данной схеме уже настроено отслеживание интерфейсов маршрутизаторов Gi0/1 (для нулевой группы)
Необходимо аналогично настроить отслеживание состояния интерфейсов Gi0/0 (для первой группы).
Для проверки корректности настройки, разорвите один из кабелей между одним из маршрутизаторов и Switch0 и запустите ping между PC0 и Server0.
На проверку отправьте получившуюся схему в формате pkt и скриншот, где виден процесс настройки маршрутизатора.

1. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/340feb9f5d4bee1a53a5f8274ddbb086422f908c/lessons_screenshots/Disaster%20recovery%20%D0%B8%20Keepalived%20Lesson%201.1.1.png)
2. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/340feb9f5d4bee1a53a5f8274ddbb086422f908c/lessons_screenshots/Disaster%20recovery%20%D0%B8%20Keepalived%20Lesson%201.1.2.png)
3. ![Lesson_1.pkt](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/340feb9f5d4bee1a53a5f8274ddbb086422f908c/lessons_screenshots/Disaster%20recovery%20%D0%B8%20Keepalived%20Lesson%201.1.pkt)

### Задание 2
 1. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/340feb9f5d4bee1a53a5f8274ddbb086422f908c/lessons_screenshots/Disaster%20recovery%20%D0%B8%20Keepalived%20Lesson%201.2.1.png)
 2. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/340feb9f5d4bee1a53a5f8274ddbb086422f908c/lessons_screenshots/Disaster%20recovery%20%D0%B8%20Keepalived%20Lesson%201.2.2.png)
 3. ![Screenshot Lesson 1](https://github.com/Anton-rus/Homework-Git-AKravchenko/blob/340feb9f5d4bee1a53a5f8274ddbb086422f908c/lessons_screenshots/Disaster%20recovery%20%D0%B8%20Keepalived%20Lesson%201.2.3.png)  
---
