# Дмитрий · Python / Rust · backend / fullstack

[![Telegram](https://img.shields.io/badge/Telegram-@lightclove-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/lightclove)
[![GitHub](https://img.shields.io/badge/GitHub-lightclove-181717?style=flat&logo=github&logoColor=white)](https://github.com/lightclove)
[![Email](https://img.shields.io/badge/Email-dm.ilyushko@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:dm.ilyushko@gmail.com)

Санкт-Петербург · удалёнка / гибрид · полная занятость · 15 лет

Инженер→backend→fullstack. API, интеграции, промышленные протоколы, телеком, поиск по документам. На Rust — сетевые клиенты и Telegram-боты: от идеи до компактного релиза под Windows, Linux и Android.

---

## Опыт

**МСА** · Fullstack · 09.2025 — н.в.  
Корпоративная RAG-платформа для машиностроения (on-prem, NDA): поиск и чат по техдокументации. Архитектура, backend, frontend, внедрение в прод — от идеи до продакшена.

- Пайплайн документов с нуля: загрузка PDF/DOCX, OCR сканов, извлечение текста, чанкинг, индекс.
- Гибридный поиск (семантика + BM25), ответы через локальные LLM (Ollama, LM Studio) со ссылками на источники.
- Индекс архива **400+ ГБ**: перестроил схему (уход с медленного ChromaDB на Qdrant), кэш эмбеддингов, инкрементальная переиндексация.
- REST-сервис сопоставления записей для ERP: нечёткий поиск, дубли и синонимы в master-data.
- SPA и админка на JS: чат, загрузка файлов, просмотр цитат, роли, мониторинг индексации в реальном времени.
- Prod: Docker, Alembic, pytest, PostgreSQL, TFS/git, Kanban.

`Python 3.13 · FastAPI · PostgreSQL · SQLAlchemy · Pydantic · sentence-transformers · FAISS · rank-bm25 · Qdrant · PyMuPDF · Tesseract · JavaScript · Docker · pytest`

**Nova Labs** · Python · 01–08.2025  
Два контракта.

*Калибровка АСУТП (производство БЛА)*  
Управление калибровочным оборудованием по Modbus TCP/RTU, сценарии калибровки. API FastAPI (старт/стоп, статус, журнал). Обмен сервисов через NATS, деплой Docker Compose (стенд = prod у заказчика).

*Обмен данными с 1С*  
ETL-сервер с нуля: выгрузка, трансформация, загрузка. REST FastAPI, валидация Pydantic, парсинг веб-источников (BeautifulSoup, Scrapy). Синхронизация 3 раза в сутки в проде.

`Python · FastAPI · pymodbus · NATS · Alembic · Pydantic · Scrapy · Docker Compose`

**Awakari** · Backend/Go · 01–08.2024 · удалённо  
Интеграционная шина на базе rss-bridge: автоматический сбор данных из соцсетей.

- Telegram-бот на Go: мультиязычность, RSS-ленты (go-telegram-bot-api, gofeed, goi18n).
- Деплой и масштабирование в Kubernetes.

`Go · Python · Kubernetes · REST API`

**Неотех** · Python · 03–12.2023  
Стартап agrotech: телеметрия и управление автоматизированной тепличной установкой — датчики, приводы, тысячи одновременных подключений.

- API-шлюз на FastAPI, нагруженные воркеры на Node.js.
- gRPC (срочные вызовы) и NATS (очереди событий/команд) между сервисами.
- PostgreSQL — справочники; TimescaleDB — телеметрия и логи.
- Нагрузочные тесты: 5000+ req/s на API управления, p99 < 50 ms.
- Несколько экземпляров сервисов в Docker Compose.

`Python 3.11 · FastAPI · gRPC · Node.js · PostgreSQL · TimescaleDB · NATS · Docker Compose`

**НТЦ ПП** · ведущий / backend · 10.2021 — 03.2023  
Два направления: NMS/EMS и интеграция корпоративных систем.

*Мониторинг телеком-оборудования*  
Автообнаружение устройств, опрос SNMP / LLDP / ICMP (netsnmp, pysnmp). Потоки через RabbitMQ, фоновые задачи Dramatiq, PostgreSQL, Alembic.

*Интеграция систем заказчика*  
Маршрутизация и преобразование сообщений: биллинг, CRM, платежи, внешние API. У каждого микросервиса своя БД — изоляция сбоев. Архитектура, техдокументация, демо заказчику.

`Python 3.10 · PostgreSQL · MongoDB · RabbitMQ · Dramatiq · Alembic · SNMP`

**Триколор** · разработчик / админ ЦОВ · 11.2020 — 10.2021  
Национальная спутниковая компания, омниканальный контакт-центр (~12,6 млн абонентов).

- Разработка и поддержка платформы на Genesys: интеграции с чат-ботами и внешними системами.
- VoIP-клиенты, новые модули, администрирование серверов.

`Python 3.8 · Genesys Composer SDK · VoIP · REST API`

**2010–2020** · инженер-программист

*Адмиралтейские верфи* · 2010–2012  
Клиент-серверные приложения и БД для промышленного предприятия.  
`C++ · Qt · Oracle 9i · PL/SQL`

*Complete* · 2012–2013 · инженер аналитической группы  
Развитие системы Hewlett Packard Project and Portfolio Management.  
`Oracle 11g`

*Авиационная и морская электроника* · 2013–2017 · инженер-программист  
Мониторинг и управление сетевой инфраструктурой промышленного и телеком-оборудования; разработка под Asterisk PBX.  
`Java · SNMP · Modbus · C++ · Python · PostgreSQL`

*Ростех, НИИ «Рубин»* · 2017–2018 · старший инженер  
CRM с нуля: учёт и автоматизация работ сервисных инженеров.  
`Python · Django · PostgreSQL · RabbitMQ`

*Институт телекоммуникаций* · 2018–2020 · инженер-программист  
ПО для интеллектуальных маршрутизаторов, мониторинговые сервисы для БЛА и телеком-систем.  
`C++ · Python · SNMP · LLDP · Docker`

---

## Проекты

**rbot** · Rust · 08.2025 — н.в.  
Telegram-бот учёта расходов: полная перепись Python→Rust в один static-бинарь (без tokio в своём коде). Postgres, Docker Alpine/musl, локальная Ollama (советы и разбор свободного ввода), polling Telegram через Tor на проде, деплой Windows→Arch, мониторинг слоёв и простоев.

`Rust · PostgreSQL · Docker · ureq · serde · Ollama · musl`

**rmalyk (Малык)** · Rust · 08.2025 — н.в.  
Windows-клиент «Tor вместо VPN»: системный прокси (локальный HTTP→SOCKS Tor), официальный Expert Bundle, мосты obfs4 / snowflake / meek, автообновление движка и откат настроек. Ноль внешних crates — std + WinAPI FFI; релизный exe < 1 МБ.

`Rust · WinAPI · Tor · SOCKS5`

**mmalyk** · Rust / Android · 08.2025 — н.в.  
Мобильный порт Малыка: UI и нативный код на Rust (JNI/NDK), VpnService + TUN→Tor SOCKS, вшитые libtor / lyrebird в APK. Тот же стек мостов и компактной сборки (opt-z, fat LTO, strip); тонкий Java только там, где требует Android.

`Rust · Android NDK · JNI · VpnService · Tor`

**[AI_Docs_Generator](https://github.com/lightclove/AI_Docs_Generator)** · Python  
RAG-чатбот по PDF через LM Studio: пайплайн документов, hybrid search / rerank, Qdrant, чат со ссылками на источники.

`Python 3.13 · FastAPI · Qdrant · LM Studio · RAG · pytest`

**[Uniface](https://github.com/lightclove/Uniface)** · Python  
Веб-сервер и браузер для входа по лицу: портал (ФИО, ИНН) → PIN Uniface → сессия; в 1С — служебный API без пароля пользователя. Liveness / антиспуф, интеграция с ERP.

`Python · FastAPI · OpenCV · 1С · uvicorn`

**[lightcloves_fin_bot](https://github.com/lightclove/lightcloves_fin_bot)** · Python  
Telegram-бот учёта расходов (исходник для rbot): aiogram 3, PostgreSQL + asyncpg, Alembic, Docker Compose, pytest.

`Python · aiogram 3 · PostgreSQL · asyncpg · Alembic · Docker · pytest`

**[MSA_Searcher_rust](https://github.com/lightclove/MSA_Searcher_rust)** · Rust  
Поиск по каталогу файлов + чат с LLM: индекс метаданных, текст read-on-query, SPA UI, один `.exe` без интерпретатора.

`Rust · JavaScript · LLM · SPA`

**[LM_Studio_1C_Proxy](https://github.com/lightclove/LM_Studio_1C_Proxy)** · Python  
Прокси FastAPI между 1С и LM Studio: нормализация запросов 1С→OpenAI API, TDD, анализ задержек локальной LLM на JSON из ERP.

`Python · FastAPI · Pydantic · LM Studio · 1С · pytest`

---

## Образование

**ПГУПС**, 2009 · прикладная математика и информатика (математик, системный программист)

---

## Стек

Python · FastAPI · PostgreSQL · Docker · Linux · Rust · C++
