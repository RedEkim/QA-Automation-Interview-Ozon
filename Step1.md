--------------------------------------------------------------------------------
[2] ЭТАП 1: BACKEND, СЕТИ & БАЗЫ ДАННЫХ (21.07.2026 — 25.10.2026)
--------------------------------------------------------------------------------

Недели 1-3 (21.07 - 10.08) | Сети, HTTP/HTTPS & REST:

 * [ ] Изучить структуру HTTP-запроса и ответа (Start line, Headers, Body).
 * [ ] Выучить ключевые заголовки: Host, Authorization, Content-Type, Cache-Control, Cookie.
 * [ ] Выучить ответы и категории статус-кодов (2xx, 3xx, 4xx, 5xx).
 * [ ] Разработать полное понимание методов REST (GET, POST, PUT, PATCH, DELETE).
 * [ ] Разобрать понятие идемпотентности методов HTTP.
 * [ ] Изучить механизмы авторизации: Cookie/Session vs JWT (Header, Payload, Signature).
 * [ ] ПРАКТИКА: Погонять запросы через Postman / Insomnia по публичным REST API.

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

  
Недели 4-6 (11.08 - 31.08) | gRPC & Сетевая архитектура:
 * [ ] Изучить архитектуру gRPC и Protocol Buffers (.proto-файлы).
 * [ ] Понять отличия gRPC от REST (Protobuf vs JSON, HTTP/2 vs HTTP/1.1, бинарность, стриминг).
 * [ ] Пошагово разложить ответ на вопрос: "Что происходит, когда вы вводите google.com в адресную строку?" (DNS -> TCP 3-way handshake -> TLS -> HTTP -> DOM/CSSOM -> Render).
 * [ ] ПРАКТИКА: Пройти тренажер secret_trainer (GitHub), поработать с gRPC через BloomRPC/Postman.

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
