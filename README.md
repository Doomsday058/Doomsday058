<h1 align="center">Привет, я Владислав 👋</h1>
<p align="center">
  <b>Аналитик-разработчик</b> · системный анализ и интеграции корпоративных систем
</p>

<p align="center">
  <a href="https://t.me/doomsdayoff"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://github.com/Doomsday058/system-analysis-portfolio"><img src="https://img.shields.io/badge/Портфолио_системного_анализа-24292F?style=for-the-badge&logo=github&logoColor=white" alt="Портфолио" /></a>
</p>

---

### 👨‍💻 Обо мне

Беру задачу как бизнес-проблему от заказчика и довожу до работающего сервиса в проде: **сбор требований → проектирование контрактов (REST API, вебхуки, OpenAPI) → реализация в коде → поддержка**. За счёт того, что стык «аналитик – разработчик» замкнут на одном человеке, смысл не теряется на передаче, а оценки сроков сходятся с реальностью.

- 🎓 Инженерное образование – **Программная инженерия, ТУСУР** (+ ДПО «Python-разработчик»).
- 🏥 Домены: **медицинский бизнес** (сеть стоматологических клиник – запись, расписания, отчётность) и **платёжные системы** (транзакционный мониторинг, success rate, инциденты провайдеров).
- 🧩 Специализация: проектирование интеграций между корпоративными системами, объектное моделирование, ETL.

---

### 🎯 Портфолио системного анализа

> **[system-analysis-portfolio](https://github.com/Doomsday058/system-analysis-portfolio)** – демонстрационные кейсы на синтетических данных: постановка задачи, проектирование интеграций и моделей данных, документация решений (BPMN, UML, ER, OpenAPI, Mermaid как diagrams-as-code).

| # | Кейс | Что показано |
|---|------|--------------|
| [01](https://github.com/Doomsday058/system-analysis-portfolio/tree/main/case-01-meeting-room-management) | Управление встречами и переговорными | Ролевая модель, конкурентный доступ к ресурсу, статусная модель, отчётность |
| [02](https://github.com/Doomsday058/system-analysis-portfolio/tree/main/case-02-booking-crm-sync) | Синхронизация онлайн-записи с CRM | Событийная интеграция, идемпотентность, разрешение конфликтов, OpenAPI-контракт |
| [03](https://github.com/Doomsday058/system-analysis-portfolio/tree/main/case-03-crm-data-pull) | Периодическая выгрузка сделок в реестр | Инкрементальная загрузка по курсору, дедупликация, НФТ |
| [04](https://github.com/Doomsday058/system-analysis-portfolio/tree/main/case-04-report-automation) | Автоматизация подготовки отчётности | Многоступенчатый пайплайн, human-in-the-loop, валидация, ПДн |

---

### 💼 Чем занимаюсь сейчас

Единственный fullstack-аналитик в компании: веду задачи от интервью с заказчиком до внедрения и поддержки в проде.

- **Интеграции CRM** – двусторонний обмен Planfix / Bitrix24 / YClients с внутренними сервисами через REST API и вебхуки: контракты обмена, идемпотентная обработка событий, дедупликация по внешним идентификаторам, разрешение конфликтов версий.
- **Модуль встреч и переговорных** – спроектировал с нуля: объектная модель, статусная схема, обработка конкурентного доступа к слотам (блокировки), два канала создания встреч.
- **ETL-пайплайны** – кросс-системная синхронизация операционных реестров (Python, Google Apps Script): модель синхронизации, дедупликация, агрегация, парсинг входящих PDF. Ручная обработка: **15 ч/нед → 1 ч** на ревью.
- **Сервис налоговой отчётности** – end-to-end на Python (pandas, PyPDF): сбор данных по API, валидация, генерация документов по шаблонам, подача через шлюз. Цикл: **3–4 дня → 2 часа**.
- **Аналитика** – SQL-запросы к данным CRM (CTE, оконные функции), метрики воронки записи пациентов, модель атрибуции источников лидов (30+ категорий).

---

<details>
<summary><b>🧪 Также разрабатываю (пет- и коммерческие проекты)</b></summary>
<br>

* **[B2B платформа для дистрибуции напитков (ТОО «VOSTOK TRADE COMPANY»)](https://github.com/Doomsday058/vostok_trade):** full-stack на **Next.js (App Router)** и **MongoDB**. Перевёл проект на единую экосистему Next.js, реализовал авторизацию (JWT), личный кабинет и модуль автоматизированной рассылки прайс-листов через SMTP.
* **[Интеллектуальный кинематографический сервис «FilmAdviser»](https://github.com/Doomsday058/online-cinema-frontend):** full-stack на **React** и **Flask/Node.js**. Поиск фильмов + генерация кратких обзоров нейросетью.
* **[AI Voice Assistant](https://github.com/Doomsday058/ai-chat-assistant):** full-stack с интеграцией **OpenAI API (GPT-4o-mini)** и **Web Speech API**. Нативный голосовой ввод, Optimistic UI, бэкенд на Node.js.
* **FoodAI (дипломная работа):** кроссплатформенное мобильное приложение на **Flutter (Dart)** – анализ пищевых привычек и персонализированные рекомендации.
* **3D-игра «Лабиринт с элементами хоррора»:** **Unity (C#)**, процедурная генерация лабиринтов.

</details>

<details>
<summary><b>🛠️ Стек технологий</b></summary>
<br>

#### 📊 Анализ и проектирование
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/BPMN_2.0-FF6D00?style=for-the-badge&logo=&logoColor=white" alt="BPMN" />
<img src="https://img.shields.io/badge/UML-1E88E5?style=for-the-badge&logo=&logoColor=white" alt="UML" />
<img src="https://img.shields.io/badge/ER--моделирование-6A1B9A?style=for-the-badge&logo=&logoColor=white" alt="ER" />
<img src="https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white" alt="OpenAPI" />
<img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=&logoColor=white" alt="REST API" />
<img src="https://img.shields.io/badge/Webhooks-4A154B?style=for-the-badge&logo=&logoColor=white" alt="Webhooks" />
<img src="https://img.shields.io/badge/ETL-2E7D32?style=for-the-badge&logo=&logoColor=white" alt="ETL" />

#### 🧠 Языки и библиотеки
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Google_Apps_Script-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Apps Script" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />

#### 🗄️ Системы, БД и инструменты
<img src="https://img.shields.io/badge/Planfix-1B74E4?style=for-the-badge&logo=&logoColor=white" alt="Planfix" />
<img src="https://img.shields.io/badge/Bitrix24-2FC7F7?style=for-the-badge&logo=&logoColor=white" alt="Bitrix24" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
<img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" alt="Confluence" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />

</details>

<details open>
<summary><b>📊 Статистика на GitHub</b></summary>
<br>

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=Doomsday058&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="Stats" />
  <br><br>
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Doomsday058&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" />
  <br><br>
  <img src="https://streak-stats.demolab.com/?user=Doomsday058&theme=tokyonight&hide_border=true" alt="Streak" />
</div>

</details>
