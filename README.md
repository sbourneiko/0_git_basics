<!----- Conversion time: 1.115 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Wed Sep 18 2019 01:01:48 GMT-0700 (PDT)
* Source doc: https://docs.google.com/open?id=1sIorEva0JHPGjUlZBihoiGIootksj8HqQUjW8Vota0c
----->




## 3. Работа с удаленными репозиториями и GitHub


### Цель работы

Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.


### Задания для выполнения



1. Зарегистрироваться на сайте github.com

![image](https://user-images.githubusercontent.com/70803921/141445950-ca6a99e4-0809-4ad1-b3a7-1c7e62e97302.png)

2. Установить на компьютере программу Git

![image](https://user-images.githubusercontent.com/70803921/141446049-1434c1e6-2028-4839-bf2c-876107c4208f.png)

3. Форкнуть данный репозиторий в свой аккаунт

![image](https://user-images.githubusercontent.com/70803921/141446129-6bc9cacc-50a5-45a4-a08b-f7b50b89ad1c.png)

4. Склонировать созданный удаленный репозиторий в директорию ~/git/test

![image](https://user-images.githubusercontent.com/70803921/141446195-dd26475e-75da-4c9a-a5d0-690dea44ef7b.png)


5. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием

![image](https://user-images.githubusercontent.com/70803921/141446277-64c56d57-b86e-42de-a0ad-3de52c9c17fd.png)

7. Фиксируем скрипт в репозитории (делаем коммит)

![image](https://user-images.githubusercontent.com/70803921/141446464-bcf63b9f-49bb-4260-8bba-5aec31bf4091.png)

8. Обновляем удаленный репозиторий репозиторий (делаем пуш)

![image](https://user-images.githubusercontent.com/70803921/141446568-a494c60b-9d0d-411f-8f2f-5d8a8b86bb74.png)

9. Через текстовый редактор добавить любую новую строку с комментарием

![image](https://user-images.githubusercontent.com/70803921/141446648-73748a6b-fdf0-47a0-87b2-0590cf4d35d4.png)


10. Сделать коммит

![image](https://user-images.githubusercontent.com/70803921/141446754-a3a0cca1-d803-455f-ba90-d19dec63d4fd.png)

11. Внести синтаксическую ошибку в скрипт

![image](https://user-images.githubusercontent.com/70803921/141446785-99d818cc-9049-456c-b08d-27f9b060b497.png)

12. Сделать коммит ошибочного скрипта

![image](https://user-images.githubusercontent.com/70803921/141446835-5cd1491a-6f02-4b02-8a61-4090fe32b8e6.png)

13. Откатываем до последней рабочей версии

![image](https://user-images.githubusercontent.com/70803921/141446890-48e91c94-2e47-44ee-b9b5-498dbaa564f8.png)

14. Просмотреть историю коммитов

![image](https://user-images.githubusercontent.com/70803921/141446957-6403dbde-d1e4-4eca-a0c7-8c279ebc33e0.png)


15. Добавить несколько коммитов произвольного содержимого

![image](https://user-images.githubusercontent.com/70803921/141447035-e0abc08c-ca86-4c0f-a1bd-3733d927b2e8.png)

16. Создать пулл реквест в данный репозиторий

![image](https://user-images.githubusercontent.com/70803921/141447063-05f00757-7c70-4acb-83cf-1090ce755c89.png)



### Контрольные вопросы


1. Зачем нужен облачный хостинг репозиториев?

Облачный хостинг репозиториев нужен для того, чтобы к репозиторию могли иметь доступ сразу несколько разработчиков вне зависимости от того, включена физическая машина с данными репозитория или нет

2. Какими основными функциями обладает сайт github.com?

С помощью сайта github.com можно загружать репозитории, клонировать, делать ответвления для тестирования, делиться репозиторием

3. Как организовать командную работу над открытым проектом?

Из корневого репозитория разработчики независимо друг от друга могут делать ответвления в свой профиль и работать над определенной частью проекта, после чего отправить отредактированную копию репозитория для дальнейшего слияния/отладки



