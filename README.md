Оптимизация запросов к БД с Redis + Hibernate 

Проект демонстрирует оптимизацию производительности часто выполняемых запросов к базе данных MySQL с помощью кеширования в Redis.

* Java: Amazon Corretto 18.0.2
* БД: MySQL 8 в Docker
* Кеш: Redis в Docker
* ORM: Hibernate 5.6
* Дополнительно: P6Spy, Lettuce, Jackson

Результаты тестирования:

    Redis:	44 ms
    MySQL:	72 ms
