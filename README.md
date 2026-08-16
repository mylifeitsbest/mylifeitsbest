<div align="center\">
  <!-- Анимированное приветствие в желтом цвете -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=F8D800&center=true&vCenter=true&width=600&lines=Привет%2C+я+Роман+(mylifeitsbest)!+👋;Бэкенд-разработчик+и+Telegram+TMA;Пишу+на+Python%2C+FastAPI+и+Vue+3;Building+robust+asynchronous+systems;" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://github.com/mylifeitsbest">
    <img src="https://img.shields.io/badge/GitHub-Profile-yellow?style=for-the-badge&logo=github&logoColor=black" />
  </a>
</p>

---\n

### 👨‍💻 Обо мне

Я — **Роман (mylifeitsbest)**, бэкенд-разработчик из России, специализирующийся на **экосистеме Telegram, асинхронных микросервисах и отказоустойчивых REST API**.

*   **Мой фокус:** Разработка интерактивных Telegram Mini Apps (TMA), асинхронных ботов и масштабируемых веб-сервисов.
*   **Главные принципы:** Чистая архитектура (Services Layer), надежность при высоких нагрузках (предотвращение Race Conditions), асинхронность и интуитивный минималистичный UI.

---\n

### 🛠 Мой технологический стек

<div align="center">

  <!-- Backend -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316194?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />

  <br/>

  <!-- Frontend & WebApps -->
  <img src="https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />

  <br/>

  <!-- Tools & Automation -->
  <img src="https://img.shields.io/badge/Telegram_API-26A69A?style=for-the-badge&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Pinia-orange?style=for-the-badge&logo=pinia&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />

</div>

---\n

### 🚀 Избранные проекты

#### 👥 [TG Support System](https://github.com/mylifeitsbest/tg-support-system)
*Асинхронная монорепозиторная система поддержки пользователей Telegram: клиент общается с ботом, а оператор отвечает через интерактивный WebApp.*
*   **Стек:** FastAPI, SQLAlchemy, SQLite, aiogram 3, Vue 3, Tailwind CSS.
*   **Особенности:**
    *   HMAC-SHA256 авторизация Telegram `initData` на бэкенде.
    *   Реализована конкурентная механика захвата чатов (Claim/Lock) с защитой от двойного ответа (409 Conflict).
    *   Покрытие E2E- и Smoke-тестами критических путей.

#### 🛍 [WB Tech Internship: REST API интернет-магазина](https://github.com/mylifeitsbest/WB-Tech-Internship-REST-API---Django)
*Тестовый REST API сервис интернет-магазина с JWT-авторизацией, защищенной транзакционной системой заказов и контролем склада.*
*   **Стек:** Python 3.11+, Django, Django REST Framework (DRF), PostgreSQL (Django ORM), Swagger (drf-spectacular), Docker.
*   **Особенности:**
    *   Выделен слой сервисов (Services Layer, `services.py`) для изоляции бизнес-логики от вьюх.
    *   Защита от Race Conditions при покупках с помощью `@transaction.atomic` и блокировки строк БД `select_for_update()`.
    *   Потоковое логирование транзакций в файл `orders.log`.

#### 🎰 [Telegram WebApp Casino & Case Opener](https://github.com/mylifeitsbest/Telegram-WebApp-Casino-Case-Opener)
*Игровой Telegram-бот со встроенными адаптивными Mini Apps для открытия кейсов и крафта.*
*   **Стек:** Python, pyTelegramBotAPI (telebot), HTML5, CSS3, Pure JavaScript, JSON-хранилище.
*   **Особенности:**
    *   Интегрированный WebApp «Кейсы» с плавной JS-анимацией прокрутки лута разной редкости.
    *   WebApp «Апгрейд» с динамическим шансом успеха и колесом фортуны.
    *   Синхронизация баланса и инвентаря в реальном времени по WebApp API.

#### 💼 [Account Manager (SPA)](https://github.com/mylifeitsbest/Account-Manager-SPA)
*Удобное Single Page Application для реактивного создания, валидации и управления учетными записями пользователей.*
*   **Стек:** Vue 3 (Composition API, `<script setup>`), Pinia, TypeScript, Vite.
*   **Особенности:**
    *   Реактивная валидация обязательных полей на событии `@blur` с визуальной подсветкой ошибок.
    *   Условный рендеринг и сброс полей в зависимости от типа аккаунта (Local / LDAP).
    *   Синхронизация с `localStorage` для персистентности данных при перезагрузке.

#### 🔐 [AnonAsk-Bot](https://github.com/mylifeitsbest/AnonAsk-Bot)
*Анонимный бот вопросов и ответов в Telegram с генерацией реферальных ссылок.*
*   **Стек:** Python 3.x, pyTelegramBotAPI (telebot).
*   **Особенности:**
    *   Уникальная система ответов на анонимные сообщения в один клик через инлайн-кнопки.
    *   Ограничение времени жизни диалогов (TTL 24 часа) с автоматической очисткой устаревших сессий в фоне через `threading`.

---\n

### 📊 Моя статистика GitHub

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=mylifeitsbest&show_icons=true&theme=dark&bg_color=0D1117&title_color=F8D800&icon_color=F8D800&text_color=FFFFFF" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mylifeitsbest&layout=compact&theme=dark&bg_color=0D1117&title_color=F8D800&text_color=FFFFFF" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mylifeitsbest&theme=dark&background=0D1117&fire=F8D800&ring=F8D800&currStreakNum=F8D800&sideNums=FFFFFF&sideLabels=FFFFFF" />
</div>

---\n

### 📬 Контакты

*   **Telegram:** [@ваша_ссылка]
*   **Email:** [ваша_почта@example.com]

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=mylifeitsbest&color=yellow&style=flat-square&label=Просмотры+профиля" alt="Просмотры профиля" />
</div>
