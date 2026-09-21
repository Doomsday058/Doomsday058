# Владислав Фёдоров

**Аналитик-разработчик · автоматизация, данные и прикладной AI**

Разбираюсь в бизнес-процессах, проектирую модели данных и интеграции,
разрабатываю инструменты для автоматизации. Работаю на стыке системного
анализа, Python-разработки и операционной аналитики.

[Telegram](https://t.me/doomsdayoff) ·
[Email](mailto:fedorov.vlad22213@mail.ru) ·
[Кейсы проектирования](https://github.com/Doomsday058/system-analysis-portfolio) ·
[Кейс анализа данных](https://github.com/Doomsday058/leads-reconciliation)

## Что я делаю

- **Автоматизация и данные:** обработка выгрузок, синхронизация реестров,
  нормализация, дедупликация, проверки качества и генерация документов.
- **Системный анализ:** требования, модели данных, роли, состояния,
  API-контракты и сценарии обработки ошибок.
- **Анализ данных:** определения показателей, сверка источников, SQL
  с CTE и оконными функциями, выводы для решений по бюджету и процессам.
- **Прикладной AI:** интеграция языковых моделей в приложения,
  разбор ответов модели и преобразование их в действия системы.
- **Разработка приложений:** интерфейсы и API для конкретных пользовательских
  сценариев. В проектах использую React / Next.js и Flutter.

## Избранные проекты

### [Tax Reporter](https://github.com/Doomsday058/tax-reporter)

Подготовка справок об оплате медицинских услуг: загрузка заявок →
нормализация → проверка бизнес-правил → PDF → пакет документов.
В рабочей версии цикл подготовки пакета сократился с 3–4 рабочих дней до ~2 часов.

В репозитории: доменная модель, объяснимые причины отклонения заявок,
режим без отправки, синтетические примеры и тесты обработки пакета.
Публичная версия рабочего проекта с демонстрационными данными и бланком.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic" />
<img src="https://img.shields.io/badge/pypdf-B30B00?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="pypdf" />
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
</p>

### [FoodAI](https://github.com/Doomsday058/FoodAI)

Трекер питания со свободным текстовым и голосовым вводом.
Ответ языковой модели преобразуется в записи о продуктах и статистику дня,
по недельной истории ассистент подсказывает, что поменять в рационе.

В репозитории: Flutter-клиент, Flask API, проектная документация,
OpenAPI, нормализация ответов модели, тесты и демо-режим без ключа OpenAI.
Дипломный проект; код восстановлен и доработан по документации ВКР.

<p>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API" />
</p>

<!--
ИИ-КЕЙС — заглушка, допилить и раскомментировать.
Идея: мультиагентная система с собственной оркестрацией (Бункер-нейрошоу).
Что показать: машина состояний вне модели, ответ по схеме с проверкой и повтором,
резервная модель при отказе основной, двухступенчатый вызов (дешёвый фильтр → дорогая модель),
контроль токенов и стоимости. Перед публикацией — вычистить ключи и приватные данные.

### [Название](https://github.com/Doomsday058/...)

Одна-две строки: что делает система и зачем.

В репозитории: …

**Python · OpenRouter / OpenAI API · …**
-->

### [Сверка заявок из трёх источников](https://github.com/Doomsday058/leads-reconciliation)

Маркетинг, CRM и сервис онлайн-записи показывают за месяц разное число заявок.
Единое определение заявки → нормализация → SQL-сверка каждого источника
водопадом → проверки качества → стоимость заявки и визита по каналам.
Итог: одна цифра вместо трёх, реальная цена заявки из Директа на 17% выше
отчётной, найденный сбой вебхуков и потерянные пропущенные звонки.

Синтетические данные с заложенными дефектами; тесты проверяют,
что анализ находит их в точности.

<p>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/matplotlib-11557C?style=flat-square&logo=&logoColor=white" alt="matplotlib" />
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
</p>

### [Кейсы системного анализа](https://github.com/Doomsday058/system-analysis-portfolio)

Четыре демонстрационных кейса: бронирование переговорных, двусторонняя
синхронизация записи с CRM, инкрементальная выгрузка и подготовка отчётности.

Требования, схемы, контракты, обработка повторных событий и ограничения решений.
Кейсы построены на синтетических данных и обобщённых сценариях.

<p>
<img src="https://img.shields.io/badge/BPMN-FF6D00?style=flat-square&logo=&logoColor=white" alt="BPMN" />
<img src="https://img.shields.io/badge/UML-1E88E5?style=flat-square&logo=&logoColor=white" alt="UML" />
<img src="https://img.shields.io/badge/ER-6A1B9A?style=flat-square&logo=&logoColor=white" alt="ER" />
<img src="https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white" alt="OpenAPI" />
<img src="https://img.shields.io/badge/Mermaid-FF3670?style=flat-square&logo=mermaid&logoColor=white" alt="Mermaid" />
</p>

### [Vostok Trade](https://github.com/Doomsday058/vostok_trade)

B2B-приложение для дистрибьютора напитков: каталог, личный кабинет,
загрузка каталога из Excel и отправка прайс-листов по email.
Импорт проверяет файл целиком до записи и заменяет каталог в транзакции:
битая строка или сбой не оставят магазин без товаров.

<p>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/Nodemailer-22B573?style=flat-square&logo=&logoColor=white" alt="Nodemailer" />
</p>

### [FilmAdviser](https://github.com/Doomsday058/filmadviser)

Личный проект: каталог TMDB, избранное, рекомендации по жанровым
предпочтениям, обзоры и поиск на естественном языке.
Рекомендации используют скоринг; языковая модель отвечает за обзоры
и преобразование поисковой фразы в фильтры.

<p>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/TMDB_API-01B4E4?style=flat-square&logo=themoviedatabase&logoColor=white" alt="TMDB API" />
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API" />
</p>

Также: [REST API каталога сериалов на Haskell / Servant](https://github.com/Doomsday058/haskell-serials-service).

## Опыт и подход

Работаю с задачами медицинского ПО — внутренние сервисы и интеграции вокруг МИС
для стоматологических клиник; до этого — аналитиком платёжных систем.
Операционные реестры, отчётность, качество данных, интеграции CRM и разбор инцидентов.
Например, синхронизация операционных реестров сократила ручную обработку
с 15 часов в неделю до часа проверки.

В решениях уделяю внимание определениям показателей, правилам обработки,
ошибкам и проверке результата. Использую AI-ассистентов при разработке;
в описаниях проектов показываю устройство решений и их ограничения.

Программная инженерия, ТУСУР · ДПО «Python-разработчик» ·
Санкт-Петербург · Английский C1.

## Стек

#### 📊 Анализ и проектирование
<p>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/BPMN_2.0-FF6D00?style=for-the-badge&logo=&logoColor=white" alt="BPMN 2.0" />
<img src="https://img.shields.io/badge/UML-1E88E5?style=for-the-badge&logo=&logoColor=white" alt="UML" />
<img src="https://img.shields.io/badge/ER--моделирование-6A1B9A?style=for-the-badge&logo=&logoColor=white" alt="ER-моделирование" />
<img src="https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white" alt="OpenAPI" />
<img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=&logoColor=white" alt="REST API" />
<img src="https://img.shields.io/badge/Webhooks-4A154B?style=for-the-badge&logo=&logoColor=white" alt="Webhooks" />
<img src="https://img.shields.io/badge/ETL-2E7D32?style=for-the-badge&logo=&logoColor=white" alt="ETL" />
</p>

#### 🧠 Разработка
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/Google_Apps_Script-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Apps Script" />
</p>

#### 🗄️ Данные, AI и инструменты
<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" alt="ClickHouse" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
<img src="https://img.shields.io/badge/Planfix-1B74E4?style=for-the-badge&logo=&logoColor=white" alt="Planfix" />
<img src="https://img.shields.io/badge/Bitrix24-2FC7F7?style=for-the-badge&logo=&logoColor=white" alt="Bitrix24" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
<img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" alt="Confluence" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

## Активность

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Doomsday058&theme=tokyonight" alt="Активность на GitHub" />
  <br><br>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Doomsday058&theme=tokyonight" alt="Языки по репозиториям" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Doomsday058&theme=tokyonight" alt="Языки по коммитам" />
</div>
