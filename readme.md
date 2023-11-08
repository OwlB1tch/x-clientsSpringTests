**Итоговая аттестация Сухоруков А.Ю.**

Запуск тестов по команде mvn test

## Задание:
Требуется сервис x-clients 

Стек автоматизации:
1. Java,
2. Любой HTTP-клиент,
3. jUnit5,
4. Allure,
5. Spring (по желанию)

Сервис доступен по – https://x-clients-be.onrender.com/

Swagger – https://x-clients-be.onrender.com/docs/#/

### Проверки:
1. Проверить, что список компаний фильтруется по параметру `active`
3. Проверить создание сотрудника в несуществующей компании
4. Проверить, что неактивный сотрудник не отображается в списке
5. Проверить, что у удаленной компании проставляется в БД поле `deletedAt`