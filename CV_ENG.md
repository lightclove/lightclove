<div align="center">

<img src="./assets/hero-neon.svg" width="100%" alt="LIGHTCLOVE"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2500&pause=700&color=00F0FF&center=true&vCenter=true&width=700&height=50&lines=RESUME+%2F%2F+CV_ENG.md;Dmitriy+%C2%B7+Python+%2F+Rust;backend+%2F+fullstack+%C2%B7+15+years" alt="typing"/>

<br/>

[![Telegram](https://img.shields.io/badge/Telegram-@lightclove-0d1117?style=for-the-badge&logo=telegram&logoColor=00f0ff&labelColor=ff2d95)](https://t.me/lightclove)
[![GitHub](https://img.shields.io/badge/GitHub-lightclove-0d1117?style=for-the-badge&logo=github&logoColor=ff2d95&labelColor=00f0ff)](https://github.com/lightclove)
[![Email](https://img.shields.io/badge/Email-dm.ilyushko@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=39ff14&labelColor=0d1117)](mailto:dm.ilyushko@gmail.com)

<img src="./assets/status-online.svg" alt="online"/>

<img src="./assets/comedy-ticker.svg" width="95%" alt="jokes"/>

<img src="./assets/divider-scan.svg" width="100%" alt="scan"/>

**Saint Petersburg** · remote / hybrid · full-time · **15 years**

> Engineer→backend→fullstack. APIs, integrations, industrial protocols, telecom, document search.  
> In **Rust** — networking clients and Telegram bots: from idea to compact releases for Windows, Linux, and Android.  
> <sub>`meetings=404` · `coffee_sla=99.9%` · `bugs→features++`</sub>

[![RU](https://img.shields.io/badge/switch-CV_RUS-0d1117?style=for-the-badge&labelColor=ff2d95&color=00f0ff)](./CV_RUS.md)
[![HOME](https://img.shields.io/badge/home-README-0d1117?style=for-the-badge&labelColor=00f0ff&color=39ff14)](./README.md)
![wotm](https://img.shields.io/badge/Works_on_my_machine-certified-0d1117?style=for-the-badge&labelColor=39ff14)

</div>

---

<details open>
<summary><b>⚡ Stack</b> <code>// what I admit in interviews</code></summary>
<br/>

<div align="center">

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00f0ff)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=39ff14)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=00f0ff)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=00f0ff)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=ff2d95)
![Rust](https://img.shields.io/badge/Rust-0d1117?style=for-the-badge&logo=rust&logoColor=ff2d95)
![C++](https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=cplusplus&logoColor=39ff14)

`Python · FastAPI · PostgreSQL · Docker · Linux · Rust · C++`

</div>
</details>

---

<details open>
<summary><b>💼 Experience — tap a sector</b> <code>// career spoilers</code></summary>
<br/>

<details open>
<summary><code>09.2025 → present</code> <b>MSA</b> · Fullstack</summary>

Corporate RAG platform for mechanical engineering (on-prem, NDA): search and chat over technical documentation. Architecture, backend, frontend, production rollout — idea to prod.

- Document pipeline from scratch: PDF/DOCX upload, OCR for scans, text extraction, chunking, index.
- Hybrid search (semantic + BM25), answers via local LLMs (Ollama, LM Studio) with source citations.
- **400+ GB** archive index: redesigned schema (ChromaDB → Qdrant), embedding cache, incremental reindexing.
- REST record-matching service for ERP: fuzzy search, duplicates and synonyms in master data.
- JS SPA and admin: chat, file upload, citation view, roles, live indexing monitoring.
- Prod: Docker, Alembic, pytest, PostgreSQL, TFS/git, Kanban.

`Python 3.13 · FastAPI · PostgreSQL · SQLAlchemy · Pydantic · sentence-transformers · FAISS · rank-bm25 · Qdrant · PyMuPDF · Tesseract · JavaScript · Docker · pytest`
</details>

<details>
<summary><code>01–08.2025</code> <b>Nova Labs</b> · Python</summary>

Two contracts.

*ASUTP calibration (UAV manufacturing)*  
Calibration equipment control over Modbus TCP/RTU, calibration scenarios. FastAPI (start/stop, status, journal). Inter-service messaging via NATS, Docker Compose deploy (staging = prod at customer site).

*1C data exchange*  
ETL server from scratch: extract, transform, load. REST FastAPI, Pydantic validation, web scraping (BeautifulSoup, Scrapy). Synced 3× daily in production.

`Python · FastAPI · pymodbus · NATS · Alembic · Pydantic · Scrapy · Docker Compose`
</details>

<details>
<summary><code>01–08.2024</code> <b>Awakari</b> · Backend/Go · remote</summary>

Integration bus on rss-bridge: automated social-media data collection.

- Telegram bot in Go: i18n, RSS feeds (go-telegram-bot-api, gofeed, goi18n).
- Deploy and scale on Kubernetes.

`Go · Python · Kubernetes · REST API`
</details>

<details>
<summary><code>03–12.2023</code> <b>Neotech</b> · Python</summary>

Agrotech startup: telemetry and control for an automated greenhouse — sensors, actuators, thousands of concurrent connections.

- FastAPI gateway, Node.js workers under load.
- gRPC (urgent calls) and NATS (event/command queues) between services.
- PostgreSQL — directories; TimescaleDB — telemetry and logs.
- Load tests: 5000+ req/s on control API, p99 < 50 ms.
- Multiple service instances via Docker Compose.

`Python 3.11 · FastAPI · gRPC · Node.js · PostgreSQL · TimescaleDB · NATS · Docker Compose`
</details>

<details>
<summary><code>10.2021 – 03.2023</code> <b>NTC PP</b> · lead / backend</summary>

Two tracks: NMS/EMS and corporate system integration.

*Telecom equipment monitoring*  
Device autodetection, SNMP / LLDP / ICMP polling (netsnmp, pysnmp). Flows via RabbitMQ, Dramatiq background jobs, PostgreSQL, Alembic.

*Customer system integration*  
Message routing and transformation: billing, CRM, payments, external APIs. Per-microservice databases — failure isolation. Architecture, tech docs, customer demos.

`Python 3.10 · PostgreSQL · MongoDB · RabbitMQ · Dramatiq · Alembic · SNMP`
</details>

<details>
<summary><code>11.2020 – 10.2021</code> <b>Tricolor</b> · developer / contact-center admin</summary>

National satellite company, omnichannel contact center (~12.6M subscribers).

- Genesys platform development and support: chatbot and external-system integrations.
- VoIP clients, new modules, server administration.

`Python 3.8 · Genesys Composer SDK · VoIP · REST API`
</details>

<details>
<summary><code>2010–2020</code> <b>software engineer</b></summary>

*Admiralty Shipyards* · 2010–2012  
Client–server apps and databases for an industrial enterprise.  
`C++ · Qt · Oracle 9i · PL/SQL`

*Complete* · 2012–2013 · analytics engineer  
Hewlett Packard Project and Portfolio Management evolution.  
`Oracle 11g`

*Aviation and marine electronics* · 2013–2017 · software engineer  
Network monitoring and control for industrial and telecom gear; Asterisk PBX development.  
`Java · SNMP · Modbus · C++ · Python · PostgreSQL`

*Rostec, Rubin Research Institute* · 2017–2018 · senior engineer  
CRM from scratch: tracking and automating field-engineer work.  
`Python · Django · PostgreSQL · RabbitMQ`

*Institute of Telecommunications* · 2018–2020 · software engineer  
Software for intelligent routers; monitoring services for UAVs and telecom systems.  
`C++ · Python · SNMP · LLDP · Docker`
</details>

</details>

---

<details open>
<summary><b>🛸 Projects</b> <code>// side quests that escaped into prod</code></summary>
<br/>

<details open>
<summary><b>Rust</b></summary>

**rbot** · 08.2025 — present  
Telegram expense tracker: full Python→Rust rewrite as one static binary (no tokio in app code). Postgres, Docker Alpine/musl, local Ollama, Telegram polling over Tor in prod, Windows→Arch deploy, layer and idle monitoring.  
`Rust · PostgreSQL · Docker · ureq · serde · Ollama · musl`

**rmalyk (Malyk)** · 08.2025 — present  
Windows “Tor instead of VPN” client: system proxy (local HTTP→SOCKS Tor), Expert Bundle, obfs4 / snowflake / meek bridges, engine auto-update. Zero external crates — std + WinAPI FFI; exe &lt; 1 MB.  
`Rust · WinAPI · Tor · SOCKS5`

**mmalyk** · 08.2025 — present  
Android port of Malyk: UI and native code in Rust (JNI/NDK), VpnService + TUN→Tor SOCKS, bundled libtor / lyrebird in the APK.  
`Rust · Android NDK · JNI · VpnService · Tor`

**[MSA_Searcher_rust](https://github.com/lightclove/MSA_Searcher_rust)**  
File-catalog search + LLM chat: metadata index, read-on-query, SPA UI, single `.exe`.  
`Rust · JavaScript · LLM · SPA`
</details>

<details>
<summary><b>Python</b></summary>

**[AI_Docs_Generator](https://github.com/lightclove/AI_Docs_Generator)**  
RAG chatbot over PDFs via LM Studio: document pipeline, hybrid search / rerank, Qdrant.  
`Python 3.13 · FastAPI · Qdrant · LM Studio · RAG · pytest`

**[Uniface](https://github.com/lightclove/Uniface)**  
Web server and browser for face-based login: portal (name, TIN) → Uniface PIN → session; 1C via service API. Liveness / anti-spoof.  
`Python · FastAPI · OpenCV · 1C · uvicorn`

**[lightcloves_fin_bot](https://github.com/lightclove/lightcloves_fin_bot)**  
Telegram expense bot (Python source for rbot): aiogram 3, PostgreSQL + asyncpg, Alembic, Docker Compose.  
`Python · aiogram 3 · PostgreSQL · asyncpg · Alembic · Docker · pytest`

**[LM_Studio_1C_Proxy](https://github.com/lightclove/LM_Studio_1C_Proxy)**  
FastAPI proxy between 1C and LM Studio: normalize 1C→OpenAI API requests, TDD, latency analysis.  
`Python · FastAPI · Pydantic · LM Studio · 1C · pytest`
</details>

</details>

---

<div align="center">

## 🎓 Education

**Emperor Alexander I St. Petersburg State Transport University (PGUPS)**, 2009 · applied mathematics and informatics (mathematician, systems programmer)

<img src="./assets/divider-scan.svg" width="100%" alt="scan"/>

`// end of transmission — CV_ENG · DNS not blamed this time`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:B026FF,50:00F0FF,100:FF2D95&height=90&section=footer&text=CV_ENG&fontSize=20&fontColor=070b12&fontAlignY=65" alt="footer"/>

</div>
