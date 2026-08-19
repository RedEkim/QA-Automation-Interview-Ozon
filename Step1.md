--------------------------------------------------------------------------------
ЭТАП 1: BACKEND, СЕТИ & БАЗЫ ДАННЫХ (21.07.2026 — 25.10.2026)
--------------------------------------------------------------------------------

Недели 1-3 (21.07 - 09.08) | Сети, HTTP/HTTPS & REST:

 * [x] Изучить структуру HTTP-запроса и ответа (Start line, Headers, Body).
 * [x] Выучить ключевые заголовки: Host, Authorization, Content-Type, Cache-Control, Cookie.
 * [x] Выучить ответы и категории статус-кодов (2xx, 3xx, 4xx, 5xx).
 * [x] Разработать полное понимание методов REST (GET, POST, PUT, PATCH, DELETE).
 * [x] Разобрать понятие идемпотентности методов HTTP.
 * [x] Изучить механизмы авторизации: Cookie/Session vs JWT (Header, Payload, Signature).
 * [x] ПРАКТИКА: Погонять запросы через Postman / Insomnia по публичным REST API.

27.07.2026 

1 hour 
- https://developer.mozilla.org/ru/docs/Web/HTTP/Guides/Overview

28.07.2026 

1 hour 
- https://developer.mozilla.org/ru/docs/Web/HTTP/Guides/Overview
- https://developer.mozilla.org/ru/docs/Web/API/Fetch_API
- https://developer.mozilla.org/ru/docs/Web/HTTP/Reference/Headers

29.07.2027 

1 hour
- https://http.cat/ 
- https://httpstatuses.io/
- [MDN: Идемпотентные методы HTTP — кратко и четко о том, почему PUT и DELETE идемпотентны, а POST — нет](https://developer.mozilla.org/ru/docs/Glossary/Idempotent)
- [Habr: Что такое REST API](https://habr.com/ru/articles/483202/)

2 hour
- [Habr: Что такое REST API](https://habr.com/ru/articles/483202/)
- [Различия REST и SOAP](https://habr.com/ru/articles/483204/)
- [Разработка REST API — что такое Contract First?](https://habr.com/ru/articles/483206/)
- [Разработка REST API — что такое Code First подход?](https://habr.com/ru/articles/483322/)

30.07.2026

1 hour
- [REST API — Что такое HATEOAS?](https://habr.com/ru/articles/483328/)
- [Рекомендации по REST API — примеры проектирования веб-сервисов на Java и Spring](https://habr.com/ru/articles/483374/)

2 hour
- [Рекомендации по REST API — примеры проектирования веб-сервисов на Java и Spring](https://habr.com/ru/articles/483374/)
- [jwt.io — официальный сайт и интерактивный отладчик JWT. Вставляешь токен и сразу видишь его структуру (Header, Payload, Signature).](https://www.jwt.io/)
- [Подробно про JWT](https://habr.com/ru/articles/842056/)

31.07.2026

1 hour
- [Подробно про JWT](https://habr.com/ru/articles/842056/)
- [JWT-токены от и до. Разбираемся с JSON Web Tokens и атаками на них](https://xakep.ru/2024/08/07/jwt-deep-dive/)
- [Introduction to JSON Web Tokens](https://www.jwt.io/introduction#what-is-json-web-token)

03.08.2026

1 hour
- [Introduction to JSON Web Tokens](https://www.jwt.io/introduction#what-is-json-web-token)
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/)
- [ReqRes.in](https://reqres.in/)
- [DummyJSON](https://dummyjson.com/)
- [Postman Learning Center](https://learning.postman.com/docs/getting-started/quick-start/)

05.08.2026

1 hour
- ПРАКТИКА: Погонять запросы через Postman / Insomnia по публичным REST API.
  - [JSONPlaceholder](https://jsonplaceholder.typicode.com/)
    - Идеален для старта. Есть эндпоинты для GET, POST, PUT, PATCH, DELETE. 
  - [ReqRes.in](https://reqres.in/)
    - Отличный эмулятор REST API, на котором удобно тренировать отправку POST-запросов с авторизацией, работу с токенами и проверку статус-кодов (200, 201, 400, 404). 
  - [DummyJSON](https://dummyjson.com/)
    - Более богатый сервис: есть эндпоинты товаров, корзины, пользователей и рабочая авторизация через JWT (/auth/login).
  - [Postman Learning Center](https://learning.postman.com/docs/getting-started/quick-start/)
    - Официальный гайд по работе с Postman (создание коллекций, передача заголовков и параметров).
   
06.08.2026

1 hour
- ПРАКТИКА: Погонять запросы через Insomnia по публичным REST API.
  - [JSONPlaceholder](https://jsonplaceholder.typicode.com/)
    - Идеален для старта. Есть эндпоинты для GET, POST, PUT, PATCH, DELETE.
  - [ReqRes.in](https://reqres.in/)
    - Отличный эмулятор REST API, на котором удобно тренировать отправку POST-запросов с авторизацией, работу с токенами и проверку статус-кодов (200, 201, 400, 404).

2 hour
- ПРАКТИКА: Погонять запросы через Insomnia по публичным REST API.
  - [ReqRes.in](https://reqres.in/)
    - Отличный эмулятор REST API, на котором удобно тренировать отправку POST-запросов с авторизацией, работу с токенами и проверку статус-кодов (200, 201, 400, 404).  

07.08.2026
1 hour
- ПРАКТИКА: Погонять запросы через Insomnia по публичным REST API.
  - [ReqRes.in](https://reqres.in/)
    - https://app.reqres.in/playground Отличный эмулятор REST API, на котором удобно тренировать отправку POST-запросов с авторизацией, работу с токенами и проверку статус-кодов (200, 201, 400, 404).
  - [DummyJSON](https://dummyjson.com/)
    - Более богатый сервис: есть эндпоинты товаров, корзины, пользователей и рабочая авторизация через JWT (/auth/login).

Недели 4-6 (10.08 - 30.08) | gRPC & Сетевая архитектура:
 * [ ] Изучить архитектуру gRPC и Protocol Buffers (.proto-файлы).
 * [ ] Понять отличия gRPC от REST (Protobuf vs JSON, HTTP/2 vs HTTP/1.1, бинарность, стриминг).
 * [ ] Пошагово разложить ответ на вопрос: "Что происходит, когда вы вводите google.com в адресную строку?" (DNS -> TCP 3-way handshake -> TLS -> HTTP -> DOM/CSSOM -> Render).
 * [ ] ПРАКТИКА: Пройти тренажер secret_trainer (GitHub), поработать с gRPC через BloomRPC/Postman.

# 📚 Источники и материалы: Недели 4–6 (10.08 – 30.08)
> **Тема:** gRPC, Protocol Buffers & Сетевая архитектура

---

## 1. gRPC, Protocol Buffers & отличие от REST

- **[Официальная документация gRPC (grpc.io)](https://grpc.io/docs/what-is-grpc/introduction/)**
  - *Ключевые темы:* Core Concepts (Unary, Server streaming, Client streaming, Bi-directional streaming).
- **[Официальная документация Protocol Buffers (protobuf.dev)](https://protobuf.dev/overview/)**
  - *Ключевые темы:* Синтаксис `proto3`, скалярные типы данных, сообщения (`message`), сервисы (`service`), нумерация полей.
- **[Habr: «Как тестировать не-REST бэкенд (gRPC)»](https://habr.com/ru/companies/qiwi/articles/588639/)**
  - Практический гайд от QIWI: разбор `.proto`-файлов, отличие gRPC от REST с точки зрения QA, нюансы тестирования.
- **[Habr: «REST vs gRPC»](https://habr.com/ru/articles/543110/)**
  - Сравнение протоколов: JSON vs Protobuf (бинарная сериализация), HTTP/1.1 vs HTTP/2 (мультиплексирование, одно TCP-соединение), производительность.

---

## 2. Разбор вопроса «Что происходит, когда вы вводите google.com?»

- **[GitHub: alex/what-happens-when (Русский перевод)](https://github.com/mkalygin/what-happens-when-RU)**
  - *Детальный алгоритм:*
    1. **DNS:** Кэш браузера $\rightarrow$ ОС $\rightarrow$ `/etc/hosts` $\rightarrow$ Резолвер провайдера $\rightarrow$ Корневые DNS-серверы.
    2. **TCP:** Трехэтапное рукопожатие (3-way handshake: `SYN` $\rightarrow$ `SYN-ACK` $\rightarrow$ `ACK`).
    3. **TLS/SSL:** Рукопожатие безопасности (обмен сертификатами, ключами, шифрование).
    4. **HTTP & DOM:** Запрос/ответ HTTP, парсинг HTML, построение DOM, CSSOM, Render Tree, Layout, Paint.
- **[Linkmeup: «Сети для самых маленьких»](https://linkmeup.ru/blog/snm/)**
  - Понятный разбор стека TCP/IP и транспортного уровня.

---

## 3. Практические инструменты и тренажеры

- **[Postman gRPC Client](https://learning.postman.com/docs/sending-requests/grpc/grpc-client-overview/)** — встроенный клиент для импорта `.proto`-файлов и выполнения gRPC-вызовов.
- **[Kreya](https://kreya.app/)** / **[BloomRPC](https://github.com/bloomrpc/bloomrpc)** — специализированные GUI-клиенты для работы с gRPC.
- **[Публичный тестовый gRPC-сервер (grpcb.in)](https://grpcb.in/)** — онлайн-песочница для тестирования Unary и Streaming вызовов.
- **[Тренажер secret_trainer на GitHub](https://github.com/search?q=secret_trainer+grpc)** — репозитории с упражнениями по тестированию gRPC.

10.08.2026

1 hour
gRPC, Protocol Buffers & отличие от REST

- [Официальная документация gRPC (grpc.io)](https://grpc.io/docs/what-is-grpc/introduction/)
  - Ключевые темы: Core Concepts (Unary, Server streaming, Client streaming, Bi-directional streaming).
- [Официальная документация Protocol Buffers (protobuf.dev)](https://protobuf.dev/overview/)
  - Ключевые темы: Синтаксис `proto3`, скалярные типы данных, сообщения (`message`), сервисы (`service`), нумерация полей.

11.08.2026
- **[Habr: REST vs gRPC. Межсервисная интеграция для начинающих](https://habr.com/ru/articles/859936/)**
1 hour

- [Официальная документация Protocol Buffers (protobuf.dev)](https://protobuf.dev/overview/)
  - Ключевые темы: Синтаксис `proto3`, скалярные типы данных, сообщения (`message`), сервисы (`service`), нумерация полей.

12.08.2026

1 hour
- **[Habr: «Как тестировать не-REST бэкенд (gRPC)»](https://habr.com/ru/companies/qiwi/articles/753778/)**
  - Практический гайд от QIWI: разбор `.proto`-файлов, отличие gRPC от REST с точки зрения QA, нюансы тестирования.
 
13.08.2026

1 hour
- **[Habr: «Как тестировать не-REST бэкенд (gRPC)»](https://habr.com/ru/companies/qiwi/articles/753778/)**
  - Практический гайд от QIWI: разбор `.proto`-файлов, отличие gRPC от REST с точки зрения QA, нюансы тестирования.
  - скачивание репо, погонял запросы в postman

18.08.2026
1 hour
- **[Habr: «REST vs gRPC»](https://habr.com/ru/articles/859936/)**
- **[GitHub: alex/what-happens-when](https://github.com/alex/what-happens-when)**
  - *Детальный алгоритм:*
    1. **DNS:** Кэш браузера $\rightarrow$ ОС $\rightarrow$ `/etc/hosts` $\rightarrow$ Резолвер провайдера $\rightarrow$ Корневые DNS-серверы.
    2. **TCP:** Трехэтапное рукопожатие (3-way handshake: `SYN` $\rightarrow$ `SYN-ACK` $\rightarrow$ `ACK`).
    3. **TLS/SSL:** Рукопожатие безопасности (обмен сертификатами, ключами, шифрование).
    4. **HTTP & DOM:** Запрос/ответ HTTP, парсинг HTML, построение DOM, CSSOM, Render Tree, Layout, Paint.

19.08.2026
1 hour
- **[GitHub: alex/what-happens-when](https://github.com/alex/what-happens-when)**
  - *Детальный алгоритм:*
    1. **DNS:** Кэш браузера $\rightarrow$ ОС $\rightarrow$ `/etc/hosts` $\rightarrow$ Резолвер провайдера $\rightarrow$ Корневые DNS-серверы.
    2. **TCP:** Трехэтапное рукопожатие (3-way handshake: `SYN` $\rightarrow$ `SYN-ACK` $\rightarrow$ `ACK`).
    3. **TLS/SSL:** Рукопожатие безопасности (обмен сертификатами, ключами, шифрование).
    4. **HTTP & DOM:** Запрос/ответ HTTP, парсинг HTML, построение DOM, CSSOM, Render Tree, Layout, Paint.
- **«Сети для самых маленьких»**
  - Понятный разбор стека TCP/IP и транспортного уровня.

Недели 7-11 (01.09 - 05.10) | Реляционные БД & SQL — PostgreSQL:
 * [ ] Освоить синтаксис: SELECT, WHERE, GROUP BY, HAVING, ORDER BY, LIMIT / OFFSET.
 * [ ] Закрепить все типы соединений: INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, CROSS JOIN.
 * [ ] Изучить подзапросы, агрегатные функции (COUNT, SUM, AVG, MIN, MAX) и CASE.
 * [ ] Разработать понимание индексов (B-Tree, Hash): почему ускоряют выборку, но замедляют запись.
 * [ ] Изучить транзакции и принципы ACID.
 * [ ] Выучить 4 уровня изоляции транзакций и феномены чтения (Dirty Read, Non-repeatable Read, Phantom Read).
 * [ ] ПРАКТИКА: Пройти SQL Academy и решить 50+ задач на sql-ex.ru.

Недели 12-14 (06.10 - 25.10) | NoSQL & Кэширование — Redis:
 * [ ] Понять назначение In-Memory БД и концепцию кэширования.
 * [ ] Изучить базовые структуры данных Redis (String, Hash, List, Set, Sorted Set) и параметр TTL.
 * [ ] ПРАКТИКА: Развернуть Redis локально и отработать основные команды в redis-cli.
