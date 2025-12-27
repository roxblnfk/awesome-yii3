# Awesome Yii3 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://www.yiiframework.com">
  <picture alt="Yii3 Logo" align="right" style="margin-right: 25px">
    <img height="125" alt="Yii3 Logo" align="right" style="margin-right: 25px" src="https://github.com/roxblnfk/awesome-yii3/blob/main/asset/yii3-logo.svg?raw=true">
  </picture>
</a>

> [Yii3](https://www.yiiframework.com) — высокопроизводительный, компонентный PHP-фреймворк для быстрой разработки современных веб-приложений.

Курируемый список потрясающих middlewares, шаблонов, рецептов, статей и инструментов для Yii3.

Предложения приветствуются!

[![English readme](https://img.shields.io/badge/English-%20%F0%9F%87%BA%F0%9F%87%B8-moccasin?style=flat&color=%23ae40A6)](README.md)
[![Russian readme](https://img.shields.io/badge/Русский-%20%F0%9F%87%B7%F0%9F%87%BA-moccasin?style=flat&color=%23ae40A6)](README-ru.md)
<br/>

## Содержание

- [Сообщество](#сообщество)
- [Обучающие материалы](#обучающие-материалы)
- [Шаблоны](#шаблоны)
- [Пакеты](#пакеты)
- [Разработка](#разработка)
- [Разное](#разное)


## Сообщество

- [Yii 3 PHP framework](https://t.me/yii3ru) — русскоязычный чат Yii3.
- [Хроники Yii3](https://t.me/yii3chronicles) — канал с новостями и обновлениями Yii3.

## Обучающие материалы

### Документация

- [yiisoft/docs] — репозиторий с документацией Yii3.

### Видео

- `2023-11-28` [Качество и контроль в большом Open Source-проекте](https://www.youtube.com/watch?v=KRDGQzY4ByA). *Александр Макаров; HighLoad++*.
- `2024-04-23` [Знакомство с Yii: история фреймворка, отличия от Laravel и Symfony, архитектура](https://www.youtube.com/watch?v=Lnicap1pmp4). *Александр Макаров; Люди и код*.
- `2024-06-27` [Про Yii3 и не только](https://www.youtube.com/watch?v=yliGczBgWmc) — о прошлом и будущем Yii, о текущем статусе Yii3. *Александр Макаров*.
- `2024-12-02` [Yii3](https://www.youtube.com/watch?v=iTwx3lZYf5s) — что умеет, чем отличается от Yii2, почему сделан так, а не иначе. *Александр Макаров; HighLoad++*.
- `2025-09-02` [Обзор релиза Yii3 App 1.0.0](https://www.youtube.com/watch?v=ksjGwhvVcN8) — первый взгляд на [yiisoft/app] v1.0.0. *Алексей Гагарин, Павел Бучнев; PHP Fart Time*.
- `2025-09-19` [SaaS-платформа на Yii3](https://www.youtube.com/watch?v=_nJLq6ME6kQ) — как Yii3 позволяет создавать слабо связанную архитектуру и легко подключать любые сторонние библиотеки. *Сергей Болтрукевич; Пых.конф’25*.
- `2025-09-19` [Внутри Yii3](https://www.youtube.com/watch?v=S9gpnjFaZY8) — *Александр Макаров; Пых.конф’25*.


### Статьи

- `2021-11-14` [Yii3 будет не тем, чего я ожидал](https://habr.com/ru/articles/589019/)
- `2022-10-26` [Yii3 Overview 1. Вступление](https://habr.com/ru/articles/695664/)
- `2022-11-07` [Yii3 Overview 2. Вспомогательные инструменты разработки](https://habr.com/ru/articles/697586/)
- `2022-11-29` [Yii3 Overview 3. Обзор app-* шаблонов и demo](https://habr.com/ru/articles/697676/)
- `2023-02-23` [Yii Validator — простой и мощный](https://habr.com/ru/articles/718444/)

### Курсы

*Всё впереди...*

## Шаблоны

- [yiisoft/app] — базовый шаблон для веб-приложений.
- [yiisoft/app-api] — базовый шаблон для API-приложений.
- [yiisoft/app-console] — базовый шаблон для консольных приложений.

## Пакеты

### Базы данных

- Yii
  - [yiisoft/db] — официальный DBAL с поддержкой нескольких СУБД.
  - [yiisoft/active-record] — тот самый Active Record.
  - Дравера: [PostgreSQL][yiisoft/db-pgsql], [MySQL][yiisoft/db-mysql], [SQLite][yiisoft/db-sqlite], [SQL Server][yiisoft/db-mssql], [Oracle][yiisoft/db-oracle].
  - Адаптеры: [Data][yiisoft/data-db], [RBAC][yiisoft/rbac-db], [Migrations][yiisoft/db-migration], [Logger][yiisoft/log-target-db], [Cache][yiisoft/cache-db], [Translation][yiisoft/translator-message-db]
- Cycle
  - [yiisoft/yii-cycle] — бридж для интеграции Cycle. Включает все наиболее востребованные модули: [DBAL][cycle/database], [ORM][cycle/orm], миграции, атрибуты и т.д.
  - [cycle/active-record] — Active Record на базе Cycle.
  - Адаптеры: [Data][yiisoft/data-cycle], [RBAC][yiisoft/rbac-cycle-db].

### Middleware

- [yiisoft/http-middleware] — набор middleware с прицелом на особенности HTTP протокола.
- [yiisoft/csrf] — middleware для защиты от CSRF.
- [yiisoft/session] — middleware для работы с сессиями и flash-сообщениями.

## Разработка

- [Buggregator](https://buggregator.dev) — инструмент для сбора логов, var-dump'ов, исключений, email'ов и прочего в целях отладки неумирающих PHP-приложений.
  - [buggregator/server] — Docker-контейнер для использования в микросервисной архитектуре.
  - [buggregator/trap] — var-dumper (клиент) и мини-сервер Buggregator для локального использования.

## Разное


[buggregator/trap]: https://github.com/buggregator/trap
[buggregator/server]: https://github.com/buggregator/server
[cycle/database]: https://github.com/cycle/database
[cycle/orm]: https://github.com/cycle/orm
[cycle/active-record]: https://github.com/cycle/active-record
[yiisoft/active-record]: https://github.com/yiisoft/active-record
[yiisoft/app]: https://github.com/yiisoft/app
[yiisoft/app-api]: https://github.com/yiisoft/app-api
[yiisoft/app-console]: https://github.com/yiisoft/app-console
[yiisoft/cache-db]: https://github.com/yiisoft/cache-db
[yiisoft/csrf]: https://github.com/yiisoft/csrf
[yiisoft/data-cycle]: https://github.com/yiisoft/data-cycle
[yiisoft/data-db]: https://github.com/yiisoft/data-db
[yiisoft/db]: https://github.com/yiisoft/db
[yiisoft/db-migration]: https://github.com/yiisoft/db-migration
[yiisoft/db-mssql]: https://github.com/yiisoft/db-mssql
[yiisoft/db-mysql]: https://github.com/yiisoft/db-mysql
[yiisoft/db-oracle]: https://github.com/yiisoft/db-oracle
[yiisoft/db-pgsql]: https://github.com/yiisoft/db-pgsql
[yiisoft/db-sqlite]: https://github.com/yiisoft/db-sqlite
[yiisoft/docs]: https://github.com/yiisoft/docs
[yiisoft/log-target-db]: https://github.com/yiisoft/log-target-db
[yiisoft/http-middleware]: https://github.com/yiisoft/http-middleware
[yiisoft/rbac-cycle-db]: https://github.com/yiisoft/rbac-cycle-db
[yiisoft/session]: https://github.com/yiisoft/session
[yiisoft/translator-message-db]: https://github.com/yiisoft/translator-message-db
[yiisoft/yii-cycle]: https://github.com/yiisoft/yii-cycle
[yiisoft/rbac-db]: https://github.com/yiisoft/rbac-db
