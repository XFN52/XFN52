<div align="center">

# XFN52

**Разработчик · Сайты · Парсеры · Боты · Серверы**

</div>

---

## Что делаю

Пишу код на **Python**, **TypeScript / React** и **PHP**.
Беру задачи, где надо не просто сверстать, а разобраться и заставить работать.

- **Сайты** — вёрстка руками, без Тильды и конструкторов. Адаптив от 320px, загрузка меньше секунды
- **Парсеры** — включая сложные JS-сайты: Playwright, разбор состояния SPA
- **Телеграм-боты** — подписки, оплата, автопродление, админка
- **Автоматизация** — обработка PDF и таблиц, генерация документов, интеграции с API нейросетей
- **Расширения для Chrome** — Manifest V3
- **Серверы** — Ubuntu, nginx, SSL с автопродлением, systemd, деплой

---

## Проекты

### 🌐 1. Сайт выездного автосервиса (AUTOHELP24)
Одностраничник под один сценарий: человек стоит на обочине и должен позвонить за 4 секунды. Прилипшая кнопка звонка, время прибытия крупно на первом экране, навигация по симптомам поломки.

`HTML5` `CSS3` `JS` · загрузка 0.9 с · PageSpeed 98 · адаптив от 320px

[Открыть демо →](https://xfn52.github.io/autohelp-landing/) · [Код на GitHub →](https://github.com/XFN52/autohelp-landing)

---

### 🧹 2. Клининговая служба «ЧИСТО 52»
Лендинг услуг уборки квартир и офисов. Калькулятор стоимости, интеграция карты Leaflet 1.9, блоки гарантий и прозрачности доверия.

`HTML5` `CSS3` `JavaScript` `Leaflet` · адаптив от 320px

[Открыть демо →](https://xfn52.github.io/chisto52-cleaning/) · [Код на GitHub →](https://github.com/XFN52/chisto52-cleaning)

---

### 💅 3. Сайт мастера маникюра «Алина»
Минималистичный премиум-лендинг с типографикой Playfair Display 900, терракотовой палитрой, тач-слайдером портфолио работ и интегрированной картой Leaflet.

`HTML5` `CSS3` `JavaScript` `Leaflet` · адаптив от 320px

[Открыть демо →](https://xfn52.github.io/manicure-alina/) · [Код на GitHub →](https://github.com/XFN52/manicure-alina)

---

### 🏠 4. Сайт установки натяжных потолков
Коммерческий лендинг с интерактивным выбором фактур потолка (глянцевые, матовые, сатиновые), галереей проектов и блоком онлайн-расчёта.

`HTML5` `CSS3` `JavaScript` · адаптив от 320px

[Открыть демо →](https://xfn52.github.io/stretch-ceilings/) · [Код на GitHub →](https://github.com/XFN52/stretch-ceilings)

---

### ⚡ 5. Neon DevOps Portfolio
Интерактивный дашборд-портфолио в стиле неонового киберпанка с анимациями канваса, статусом сервисов и мониторингом стека.

`React 19` `Vite` `TypeScript` `TailwindCSS` `Lucide Icons`

[Открыть демо →](https://xfn52.github.io/neon-devops-portfolio/) · [Код на GitHub →](https://github.com/XFN52/neon-devops-portfolio)

---

### 🔄 Миграция туристического портала: WordPress → PHP 8
Сайт на WP с плагинами открывался 6 секунд, админка висла. Перенёс на чистый PHP 8 + MariaDB со своей админ-панелью. 32 объекта каталога с галереями, таблицами цен и геоданными — с сохранением URL и счётчиков просмотров. Карты на Leaflet без платных ключей.

`PHP 8` `MariaDB` `Leaflet` `Python` (скрипт конвертации шаблонов)

---

### 🤖 Local Proxy API (FastAPI + Playwright)
Сервер с OpenAI-совместимым эндпоинтом, который под капотом асинхронно управляет Chromium. Изолированные сессии с ротацией, мультимодальность, retry, обработка модальных окон и падений браузера. Половина кода — крайние случаи, на них ушло больше всего времени.

`Python` `FastAPI` `Playwright` `asyncio` `pydantic`

[Код на GitHub →](https://github.com/XFN52/xray-telemt-proxy)

---

### 🧩 Chrome-расширение: переводчик на Gemini API
Manifest V3: service worker, content-скрипты, popup. Перевод выделенного текста всплывающей панелью на любой странице, распознавание текста с картинок, ротация нескольких API-ключей, интерфейс на 13 языках.

`JavaScript` `Manifest V3` `Chrome APIs` `Gemini API`

[Код на GitHub →](https://github.com/XFN52/ai-translator-gemini-api)

---

### 📄 PDF → LaTeX с автопочинкой компиляции
Скрипт превращает PDF-лекции в LaTeX. Самое интересное — он сам чинит ошибки компиляции: читает лог `pdflatex`, получает правки от модели и применяет их к файлу. Три попытки, потом честно говорит, где застрял.

`Python` `PyMuPDF` `LLM API` `subprocess`

[Код на GitHub →](https://github.com/XFN52/otcifrovka_lekchii)

---

### 🖥 Развёртывание сервисов на VPS
Ubuntu с нуля: nginx как reverse proxy, ECC-сертификаты Let's Encrypt через acme.sh с автопродлением по cron, systemd-юниты для демонов, bash-скрипты установки одной командой.

`Ubuntu` `Nginx` `systemd` `acme.sh` `Bash` `SQLite`

---

## Стек

**Языки** — Python · PHP · JavaScript · TypeScript  
**Backend** — FastAPI · MySQL / MariaDB · SQLite  
**Frontend** — React 19 · Vite · HTML5 / CSS3 · Vanilla JS  
**Инструменты** — Playwright · BeautifulSoup · aiogram · Chrome Extensions API  
**Сервер** — Ubuntu · Nginx · systemd · SSL  

---

<div align="center">

<details>
<summary>English</summary>

Developer. Websites, web scraping, Telegram bots, server setup.
Python · PHP · TypeScript / React · FastAPI · Playwright · Linux.

</details>

</div>
