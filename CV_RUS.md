<div align="center">

<img src="https://raw.githubusercontent.com/lightclove/lightclove/main/assets/hero-neon.svg?v=19aee6f" width="100%" alt="LIGHTCLOVE"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2500&pause=700&color=38BDF8&center=true&vCenter=true&width=700&height=50&lines=%D0%A0%D0%95%D0%97%D0%AE%D0%9C%D0%95+%2F%2F+CV_RUS.md;%D0%94%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B9+%C2%B7+Python+%2F+Rust;%D0%B1%D0%B0%D0%BA%D0%B5%D0%BD%D0%B4+%2F+fullstack+%C2%B7+15+%D0%BB%D0%B5%D1%82" alt="typing"/>

<br/>

[![Telegram](https://img.shields.io/badge/Telegram-@lightclove-0d1117?style=for-the-badge&logo=telegram&logoColor=38BDF8&labelColor=38BDF8)](https://t.me/lightclove)
[![GitHub](https://img.shields.io/badge/GitHub-lightclove-0d1117?style=for-the-badge&logo=github&logoColor=818CF8&labelColor=818CF8)](https://github.com/lightclove)
[![Email](https://img.shields.io/badge/Email-dm.ilyushko@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=94A3B8&labelColor=0d1117)](mailto:dm.ilyushko@gmail.com)

<img src="https://raw.githubusercontent.com/lightclove/lightclove/main/assets/status-online.svg?v=19aee6f" alt="online"/>

<img src="https://raw.githubusercontent.com/lightclove/lightclove/main/assets/comedy-ticker.svg?v=19aee6f" width="95%" alt="jokes"/>

<img src="https://raw.githubusercontent.com/lightclove/lightclove/main/assets/divider-scan.svg?v=19aee6f" width="100%" alt="scan"/>

**Санкт-Петербург** · удалёнка / гибрид · полная занятость · **15 лет**

> Инженер→backend→fullstack. API, интеграции, промышленные протоколы, телеком, поиск по документам.  
> На **Rust** — сетевые клиенты и Telegram-боты: от идеи до компактного релиза под Windows, Linux и Android.  
> <sub>`meetings=404` · `coffee_sla=99.9%` · `bugs→features++`</sub>

[![EN](https://img.shields.io/badge/switch-CV_ENG-0d1117?style=for-the-badge&labelColor=818CF8&color=818CF8)](./CV_ENG.md)
[![HOME](https://img.shields.io/badge/home-README-0d1117?style=for-the-badge&labelColor=38BDF8&color=64748B)](./README.md)
![wotm](https://img.shields.io/badge/Works_on_my_machine-certified-0d1117?style=for-the-badge&labelColor=64748B)

</div>

---

<details open>
<summary><b>⚡ Стек</b> <code>// то, в чём признаюсь на собесе</code></summary>
<br/>

<div align="center">

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=38BDF8)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=94A3B8)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=38BDF8)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=38BDF8)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=818CF8)
![Rust](https://img.shields.io/badge/Rust-0d1117?style=for-the-badge&logo=rust&logoColor=818CF8)
![C++](https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=cplusplus&logoColor=94A3B8)

`Python · FastAPI · PostgreSQL · Docker · Linux · Rust · C++`

</div>
</details>

---

<details open>
<summary><b>💼 Опыт — кликни сектор</b> <code>// спойлеры карьеры</code></summary>
<br/>

<details open>
<summary><code>09.2025 → н.в.</code> <b>МСА</b> · Fullstack</summary>

Корпоративная RAG-платформа для машиностроения (on-prem, NDA): поиск и чат по техдокументации. Архитектура, backend, frontend, внедрение в прод — от идеи до продакшена.

- Пайплайн документов с нуля: загрузка PDF/DOCX, OCR сканов, извлечение текста, чанкинг, индекс.
- Гибридный поиск (семантика + BM25), ответы через локальные LLM (Ollama, LM Studio) со ссылками на источники.
- Индекс архива **400+ ГБ**: перестроил схему (уход с медленного ChromaDB на Qdrant), кэш эмбеддингов, инкрементальная переиндексация.
- REST-сервис сопоставления записей для ERP: нечёткий поиск, дубли и синонимы в master-data.
- SPA и админка на JS: чат, загрузка файлов, просмотр цитат, роли, мониторинг индексации в реальном времени.
- Prod: Docker, Alembic, pytest, PostgreSQL, TFS/git, Kanban.

`Python 3.13 · FastAPI · PostgreSQL · SQLAlchemy · Pydantic · sentence-transformers · FAISS · rank-bm25 · Qdrant · PyMuPDF · Tesseract · JavaScript · Docker · pytest`
</details>

<details>
<summary><code>01–08.2025</code> <b>Nova Labs</b> · Python</summary>

Два контракта.

*Калибровка АСУТП (производство БЛА)*  
Управление калибровочным оборудованием по Modbus TCP/RTU, сценарии калибровки. API FastAPI (старт/стоп, статус, журнал). Обмен сервисов через NATS, деплой Docker Compose (стенд = prod у заказчика).

*Обмен данными с 1С*  
ETL-сервер с нуля: выгрузка, трансформация, загрузка. REST FastAPI, валидация Pydantic, парсинг веб-источников (BeautifulSoup, Scrapy). Синхронизация 3 раза в сутки в проде.

`Python · FastAPI · pymodbus · NATS · Alembic · Pydantic · Scrapy · Docker Compose`
</details>

<details>
<summary><code>01–08.2024</code> <b>Awakari</b> · Backend/Go · удалённо</summary>

Интеграционная шина на базе rss-bridge: автоматический сбор данных из соцсетей.

- Telegram-бот на Go: мультиязычность, RSS-ленты (go-telegram-bot-api, gofeed, goi18n).
- Деплой и масштабирование в Kubernetes.

`Go · Python · Kubernetes · REST API`
</details>

<details>
<summary><code>03–12.2023</code> <b>Неотех</b> · Python</summary>

Стартап agrotech: телеметрия и управление автоматизированной тепличной установкой — датчики, приводы, тысячи одновременных подключений.

- API-шлюз на FastAPI, нагруженные воркеры на Node.js.
- gRPC (срочные вызовы) и NATS (очереди событий/команд) между сервисами.
- PostgreSQL — справочники; TimescaleDB — телеметрия и логи.
- Нагрузочные тесты: 5000+ req/s на API управления, p99 < 50 ms.
- Несколько экземпляров сервисов в Docker Compose.

`Python 3.11 · FastAPI · gRPC · Node.js · PostgreSQL · TimescaleDB · NATS · Docker Compose`
</details>

<details>
<summary><code>10.2021 – 03.2023</code> <b>НТЦ ПП</b> · ведущий / backend</summary>

Два направления: NMS/EMS и интеграция корпоративных систем.

*Мониторинг телеком-оборудования*  
Автообнаружение устройств, опрос SNMP / LLDP / ICMP (netsnmp, pysnmp). Потоки через RabbitMQ, фоновые задачи Dramatiq, PostgreSQL, Alembic.

*Интеграция систем заказчика*  
Маршрутизация и преобразование сообщений: биллинг, CRM, платежи, внешние API. У каждого микросервиса своя БД — изоляция сбоев. Архитектура, техдокументация, демо заказчику.

`Python 3.10 · PostgreSQL · MongoDB · RabbitMQ · Dramatiq · Alembic · SNMP`
</details>

<details>
<summary><code>11.2020 – 10.2021</code> <b>Триколор</b> · разработчик / админ ЦОВ</summary>

Национальная спутниковая компания, омниканальный контакт-центр (~12,6 млн абонентов).

- Разработка и поддержка платформы на Genesys: интеграции с чат-ботами и внешними системами.
- VoIP-клиенты, новые модули, администрирование серверов.

`Python 3.8 · Genesys Composer SDK · VoIP · REST API`
</details>

<details>
<summary><code>2010–2020</code> <b>инженер-программист</b></summary>

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
</details>

</details>

---

<details open>
<summary><b>🛸 Проекты</b> <code>// сайдквесты, сбежавшие в прод</code></summary>
<br/>

<details open>
<summary><b>Rust</b></summary>

**rbot** · 08.2025 — н.в.  
Telegram-бот учёта расходов: полная перепись Python→Rust в один static-бинарь (без tokio в своём коде). Postgres, Docker Alpine/musl, локальная Ollama, polling Telegram через Tor на проде, деплой Windows→Arch, мониторинг слоёв и простоев.  
`Rust · PostgreSQL · Docker · ureq · serde · Ollama · musl`

**rmalyk (Малык)** · 08.2025 — н.в.  
Windows-клиент «Tor вместо VPN»: системный прокси (локальный HTTP→SOCKS Tor), Expert Bundle, мосты obfs4 / snowflake / meek, автообновление движка. Ноль внешних crates — std + WinAPI FFI; exe < 1 МБ.  
`Rust · WinAPI · Tor · SOCKS5`

**mmalyk** · 08.2025 — н.в.  
Мобильный порт Малыка: UI и нативный код на Rust (JNI/NDK), VpnService + TUN→Tor SOCKS, вшитые libtor / lyrebird в APK.  
`Rust · Android NDK · JNI · VpnService · Tor`

**[MSA_Searcher_rust](https://github.com/lightclove/MSA_Searcher_rust)**  
Поиск по каталогу файлов + чат с LLM: индекс метаданных, read-on-query, SPA UI, один `.exe`.  
`Rust · JavaScript · LLM · SPA`
</details>

<details>
<summary><b>Python</b></summary>

**[AI_Docs_Generator](https://github.com/lightclove/AI_Docs_Generator)**  
RAG-чатбот по PDF через LM Studio: пайплайн документов, hybrid search / rerank, Qdrant.  
`Python 3.13 · FastAPI · Qdrant · LM Studio · RAG · pytest`

**[Uniface](https://github.com/lightclove/Uniface)**  
Веб-сервер и браузер для входа по лицу: портал (ФИО, ИНН) → PIN Uniface → сессия; в 1С — служебный API. Liveness / антиспуф.  
`Python · FastAPI · OpenCV · 1С · uvicorn`

**[lightcloves_fin_bot](https://github.com/lightclove/lightcloves_fin_bot)**  
Telegram-бот учёта расходов (исходник для rbot): aiogram 3, PostgreSQL + asyncpg, Alembic, Docker Compose.  
`Python · aiogram 3 · PostgreSQL · asyncpg · Alembic · Docker · pytest`

**[LM_Studio_1C_Proxy](https://github.com/lightclove/LM_Studio_1C_Proxy)**  
Прокси FastAPI между 1С и LM Studio: нормализация 1С→OpenAI API, TDD, анализ задержек.  
`Python · FastAPI · Pydantic · LM Studio · 1С · pytest`
</details>

</details>

---

<div align="center">

## 🎓 Образование

**ПГУПС**, 2009 · прикладная математика и информатика (математик, системный программист)

<img src="https://raw.githubusercontent.com/lightclove/lightclove/main/assets/divider-scan.svg?v=19aee6f" width="100%" alt="scan"/>

`// end of transmission — CV_RUS · DNS not blamed this time`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F0FF,50:FF2D95,100:B026FF&height=90&section=footer&text=CV_RUS&fontSize=20&fontColor=070b12&fontAlignY=65" alt="footer"/>

</div>
