## Дипломная работа по курсу «PHP/SQL: back-end разработка и базы данных»

+ Разработан типовой сервис вопросов и ответов. Pеализована клиентская часть сервиса и интерфейс администратора.
+ Система реализована на PHP, использована MVC архитектура, компоненты реализованы с использованием ООП, данные администраторов, тем, вопросов и ответов хранится в СУБД MySQL
+ ссылка интерфейс [Клиентская часть](http://university.netology.ru/u/nfomina/php/index.php?c=front&a=categories&categoryId=all)
+ ссылка интерфейс [Администратор](http://university.netology.ru/u/nfomina/php/index.php) (пароль: admin, логин: admin)

### Клиентская часть
![Клиентская часть](./resources/clientInt.jpg)

+ Пользователи могут просматривать категории, вопросы и ответы.
+ Любой пользователь может задать вопрос, указав своё имя, адрес электронной почты, выбрав категорию и написав текст вопроса.

### Интерфейс администратора
![Интерфейс администратора 1](./resources/admin_1.jpg)
![Интерфейс администратора 2](./resources/admin_2.jpg)
+ Для попадания в интерфейс администратора нужно ввести логин и пароль.
+ По умолчанию создан единственный администратор с логином admin и паролем admin.
+ Раздел общее: кол-во вопросов в каждой категории, кол-во вопросов без ответа и кол-во администраторов
+ Раздел администраторы: список администраторов с возможностью удалить или изменить пароль, и добавить нового администратора
+ Раздел категории: список категорий, общее кол-во вопросов в них, опубликованных, без ответа, скрытых. Возможножно просмотреть все вопросы в теме, удалить категорию с вопросами и добавить новую категорию.
+ Раздел вопросы без ответа: список вопросов без ответа, возможно удалить, изменить статус и редактировать
+ Редактировать вопрос: изменить категорию, имя автора, заголовок вопроса, контент вопроса, ответ на вопрос. Возможно публикация на сайт или скрыть вопрос


### Инструкции по установке 
+ Сделать клон репозитория
+ Поместить содержимое папки на ваш сервер
+ Загрузить в базу данные из dump.sql
+ В файле config.php указать имя базы данных, логин и пароль к ней


### UML-схема базы данных
![UML-схема базы данных](./resources/uml.jpg)

