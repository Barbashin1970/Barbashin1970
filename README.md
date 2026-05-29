# Привет 👋 Меня зовут Олег Барбашин

Я строю **сложные системы вместе с ИИ** — параллельно растёт и код, и документация.
ИИ для меня не вспомогательный инструмент, а **соисполнитель**, который пишет наравне со мной.
Меня интересует **исследование границ** того, что эта связка (человек + большая модель) может сделать за итерацию.

---

## 🎿 SKICODING — мой авторский метод

> **Чередование текстовых (`.md`) и кодовых (`commit`) шагов**, как лыжных следов: левая → правая → левая → правая.

Соло-разработчик с большой моделью рискует скатиться в одну из двух ловушек: **code-rush** (через неделю 5 несовместимых архитектур) или **doc-paralysis** (4000 строк md без единой строки кода). SKICODING — компромисс: **каждый шаг оставляет проверяемый артефакт**, который сверяется с предыдущим.

6 шагов в цикле:

```
1. Аудит-md (что нашли, что закроем)
2. Реализация фаз     ← commit
3. Актуализация документации
4. Новые UI-фичи      ← commit
5. Backlog отложенного с обязательным «Почему»
6. Тесты              ← commit
→ возврат к 1
```

Применил на **8+ итерациях в продакшен-проекте** (онтологии регламентов), зафиксировал как переиспользуемый skill. Подход универсален для любой соло-разработки с LLM.

[![SKICODING — полная версия с code-patterns, security-checklist, test-discipline](https://img.shields.io/badge/📖_Читать_SKICODING_(675_строк)-FF6B35?style=for-the-badge)](https://github.com/Barbashin1970/RAGRAF/blob/main/docs/SKILL-SKICODING.md)

---

## 🧪 Почему агентный код у меня даёт ×50 к скорости

В IT я с **2022 года** — пришёл из тестирования и системного анализа. До того, как взять в соавторы LLM, я несколько лет профессионально занимался двумя вещами:

- **Тестирование систем** — генерация сценариев, классы эквивалентности, граничные значения, тест-комплекты, баг-репорты.
- **Спеки и ТЗ** — формулировка требований по ГОСТ 19.201, тест-планы, критерии начала/завершения, риск-анализ.

Это **ровно те две компетенции, которые нужны для агентного программирования**:

| Что требует LLM-разработка | Что я уже умел делать |
|----------------------------|----------------------|
| Чётко поставить задачу одной итерации | Писать спек, который не толкует двояко |
| Проверить, что модель сделала именно то | Прогонять тест-кейсы и негативные сценарии |
| Поймать регрессию на ранней стадии | Юнит-тесты + границы + туры по фичам |
| Разложить сложное на проверяемые шаги | Декомпозиция в тест-плане |

Поэтому SKICODING — это не «модный приём», а **прямой перенос QA-цикла на соло-разработку с моделью**. Каждая текстовая итерация = ревью спека. Каждая кодовая = прогон тест-кейса.

### 📊 Замер ×50

На последних проектах я мерил темп vs мой первый командный опыт в IT-команде 2022 года:

```
2022 — командный pace:    1 фича за 1-2 недели (с PM, dev, QA, ревью)
2026 — SKICODING pace:    1 фича за 2-4 часа (соло, с LLM, теми же QA-практиками)
                          ──────────────────
                                ×50
```

Это не про «модель быстро пишет код». Это про **отсутствие задержек** между ролями: я сам себе PM, dev и QA, между ними **нет очередей и согласований**. Качество держится за счёт того, что **ни одну из трёх ролей я не пропускаю** — все три играю на каждой итерации.

---

## 🧰 Стек, в котором я работаю

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)

**Семантика и онтологии**

![RDF](https://img.shields.io/badge/RDF/Turtle-005A9C?style=for-the-badge)
![SHACL](https://img.shields.io/badge/SHACL-2D8B57?style=for-the-badge)
![OWL](https://img.shields.io/badge/OWL-7B3F00?style=for-the-badge)

**ИИ и инструменты**

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 🚀 Проекты

### 🌐 Живые демо — открой и потрогай

**🏢 Системы для бизнеса и нормативки**

| Проект | Что это | Открыть |
|--------|---------|---------|
| **RAGRAF** | Контроль регламентов через онтологии (SHACL + DuckDB) | [![Open](https://img.shields.io/badge/▶_Открыть-1E40AF?style=for-the-badge)](https://ragraf.up.railway.app/) |
| **AI-SKLAD** | ИИ-анализ остатков склада | [![Open](https://img.shields.io/badge/▶_Открыть-DC2626?style=for-the-badge)](https://ai-sklad.vercel.app/) |
| **STROY (Safety Builder)** | Text-to-SQL по охране труда: чек-листы СИЗ, наряды-допуски | [![Open](https://img.shields.io/badge/▶_Открыть-EA580C?style=for-the-badge)](https://safety-builder.streamlit.app/) |
| **NSK OpenData Bot** | Бот по открытым данным Новосибирска (IQ-roadmap) | [![Open](https://img.shields.io/badge/▶_Открыть-475569?style=for-the-badge)](https://nsk-opendata-bot.up.railway.app/) |

**🔬 Научная разработка — верификаторы кода**

| Проект | Что это | Открыть |
|--------|---------|---------|
| **POLINOM-JAVA** | Верификатор кода на алгоритмические риски на JVM + JMH-бенчмарки | [![Open](https://img.shields.io/badge/▶_Открыть-B45309?style=for-the-badge)](https://polinom-java.up.railway.app/) |

> Сигма-методология выявляет полиномиальные риски сложности в коде. POLINOM-JAVA — перенос правил на JVM.

**🎮 Мультиплеер-игры — мой эксперимент с фронт-бэк**

Игры для **2-4 игроков**, можно играть **удалённо по сети**. Учусь строить полноценные системы с realtime-синхронизацией состояния, лобби, ботами и WebSocket-связью клиента и сервера.

| Проект | Что это | Открыть |
|--------|---------|---------|
| **Orbital Race** (GONKA) | PWA-гонки на React 19, до 4 игроков | [![Open](https://img.shields.io/badge/▶_Открыть-059669?style=for-the-badge)](https://gonka-two.vercel.app/) |
| **Tigra Dice** (KNIFFEL) | PWA-Яцзы, до 4 игроков | [![Open](https://img.shields.io/badge/▶_Открыть-0891B2?style=for-the-badge)](https://tigra-dice.vercel.app/) |

**✨ Личные и обучающие**

| Проект | Что это | Открыть |
|--------|---------|---------|
| **SOFIA** | Персональная ароматерапия по Юнгу и нумерологии | [![Open](https://img.shields.io/badge/▶_Открыть-7C3AED?style=for-the-badge)](https://sofia-europe.vercel.app/) |
| **Harry Potter Quiz** | Квиз по вселенной HP | [![Open](https://img.shields.io/badge/▶_Открыть-92400E?style=for-the-badge)](https://harrypotterquiz-tau.vercel.app/home) |

**🛠 Полезные инструменты**

| Проект | Что это | Открыть |
|--------|---------|---------|
| **SmartCity Prompt** | Конструктор промптов для городских и нормативных задач | [![Open](https://img.shields.io/badge/▶_Открыть-0E7490?style=for-the-badge)](https://smartcityprompt.vercel.app/) |

---

### Заказные системы

[![RAGRAF](https://img.shields.io/badge/RAGRAF-Контроль_регламентов_через_онтологии-1E40AF?style=for-the-badge)](https://ragraf.up.railway.app/)
[![LEYKA](https://img.shields.io/badge/LEYKA-Управление_задачами_с_КОСГУ--категоризацией-0F766E?style=for-the-badge)](https://github.com/Barbashin1970)

> Полный цикл: ТЭО → ТЗ по ГОСТ 19.201 → архитектура → реализация → ГОСТ-19 комплект документации. Контракты с НГУ и коммерческими заказчиками.

### Демо для бизнеса

[![AI-SKLAD](https://img.shields.io/badge/AI--SKLAD-ИИ--анализ_остатков_склада-DC2626?style=for-the-badge)](https://ai-sklad.vercel.app/)
[![STROY](https://img.shields.io/badge/STROY-Text--to--SQL_по_охране_труда-EA580C?style=for-the-badge)](https://safety-builder.streamlit.app/)
[![SmartCityPrompt](https://img.shields.io/badge/SmartCity_Prompt-Конструктор_промптов-0E7490?style=for-the-badge)](https://smartcityprompt.vercel.app/)

### Мультиплеер-игры (эксперимент с фронт-бэк)

[![GONKA](https://img.shields.io/badge/Orbital_Race-PWA--гонки_2--4_игрока_по_сети-059669?style=for-the-badge)](https://gonka-two.vercel.app/)
[![KNIFFEL](https://img.shields.io/badge/Tigra_Dice-Яцзы_2--4_игрока_по_сети-0891B2?style=for-the-badge)](https://tigra-dice.vercel.app/)

### Личные и обучающие

[![SOFIA](https://img.shields.io/badge/SOFIA-Ароматерапия_по_Юнгу_и_нумерологии-7C3AED?style=for-the-badge)](https://sofia-europe.vercel.app/)
[![HarryPotter](https://img.shields.io/badge/Harry_Potter_Quiz-Квиз_по_вселенной_HP-92400E?style=for-the-badge)](https://harrypotterquiz-tau.vercel.app/home)

### Научная разработка — верификаторы кода

[![POLINOM](https://img.shields.io/badge/POLINOM-Верификатор_алгоритмических_рисков_(Python)-6366F1?style=for-the-badge)](https://github.com/Barbashin1970)
[![POLINOM-JAVA](https://img.shields.io/badge/POLINOM--JAVA-Верификатор_на_JVM_+_JMH-B45309?style=for-the-badge)](https://polinom-java.up.railway.app/)
[![NSK_OpenData_Bot](https://img.shields.io/badge/NSK_OpenData_Bot-IQ--roadmap_паттерн-475569?style=for-the-badge)](https://nsk-opendata-bot.up.railway.app/)

> **POLINOM / POLINOM-JAVA — научные верификаторы кода на алгоритмические риски.** Опираются на Сигма-методологию (полиномиальная сложность), выявляют потенциально опасные паттерны до runtime.

---

## 🤝 Давай работать вместе

**У тебя есть идея сложной системы — приходи.**

Я ищу задачи, в которых:

- ✅ Нужно **спроектировать с нуля** и не повторять чужие решения.
- ✅ Есть **домен с правилами и онтологиями** (регламенты, нормативка, чек-листы, графы знаний).
- ✅ Заказчик готов **двигаться итерациями** с живой документацией — а не «дайте спек на 200 страниц, через год вернёмся».
- ✅ Можно **подружить ИИ с детерминированной логикой** — не «свободный LLM-агент», а гибрид «LLM для парсинга → SQL/SPARQL для генерации».

**Что ты получишь:**

- Систему **+ полный комплект документации** (ТЗ ГОСТ 19.201, архитектура, тест-стратегия, README билингвально, отчёты).
- **Прозрачный процесс** — каждый коммит виден, каждое решение зафиксировано как ADR.
- **Никаких чёрных ящиков** — даже ИИ-логика детерминирована и проверяема.

📩 **Напиши**, опиши задачу — и я скажу, через сколько итераций мы её закроем.

---

## 📬 Контакты

- ✉️ **Email:** banksnab@gmail.com
- 💼 **GitHub:** [@Barbashin1970](https://github.com/Barbashin1970)
- 📍 **Локация:** Новосибирск, Россия

---

<div align="center">

**«Сложные системы не строятся в одиночку. Я приглашаю в соавторы и людей, и ИИ — и слежу, чтобы все следы оставались проверяемыми.»**

</div>
