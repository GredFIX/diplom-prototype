# Дипломная работа.

## О сервисе
Backend написан на Python / Flask, frontend на HTML+CSS.
Для запуска необходим Docker.

## Установка и запуск
```bash
$ docker-compose up --build
```

## Какие есть логины и пароли?
Для простоты все пароли - password, но в базе данных они хешированы, поэтому выглядят по-разному
Логины:
- Инструктора и ученики: смотреть в **db/create_fixtures.sql**
- Админ: **admin**