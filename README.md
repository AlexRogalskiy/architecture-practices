Ключевые практики архитектора ПО 
=================================
3 дня

Для кого
=========
- [ ] **Системные архитекторы**
- [ ] **Разработчики с функцией системного проектирования**
- [ ] Системные аналитики
- [ ] Enterprise- и Solution-архитекторы
- [ ] Разработчики

<!--
На выходе
==========
Участники смогут
- [ ] 
и получат инструменты для использования на производстве
- [ ] Архитектурный документ
-->

Программа
=========
18 ак.ч.

Знакомство (1 час, из них 0.5 практики)
----------
- [ ] Формат: 10:00 – 15:00
- [ ] Перерывы: 10:50 – 11:05, 12:00 – 13:00, 13:50 – 14:05 
- [ ] Материалы
- [ ] Разбивка на команды по трое
- [ ] Знакомство и сбор проблем участников
- [ ] Обзор тренинга

Что такое архитектура (1/0.5)
---------------------
- [ ] Что такое архитектура?
- [ ] Какова цель архитектурной работы? 
- [ ] На какие вопросы должна отвечать архитектура?
- [ ] Начинаем «Шаблон архитектурного документа с примерами» by example
- ключевые решения,
- структурная декомпозиция,
- договоренности/правила/guidelines развития

Стейкхолдеры проекта/продукта (1/0.5)
------------------------------
- [ ] На всем жизненном цикле системы кого касаются архитектурные решения? Кто участвует в разработке, приемке и эксплуатации системы? Кто несет ответственность за какой-либо аспект системы?
- [ ] В чем их интересы?
- [ ] Как можно выразить интересы в форме рисков?
- [ ] Какие артефакты архитектор ждет от них?
- [ ] Какие артефакты они ожидают от архитектора?
- [ ] Продолжаем Шаблон архитектурного документа
- коммуникационные задачи архитектора

Жизненный цикл системы (1/0.5)
-------------------------------
- [ ] Какие этапы/вехи можете выделить в ЖЦ проекта/продукта?
- [ ] Каковы критерии приемки для этих этапов?
- [ ] Какие артефакты должны измениться на этих этапах?
- [ ] Как можно выразить этапы в терминах рисков?
- [ ] Какие требования следует добавить в начало ЖЦ?
- [ ] Связываем Шаблон архитектурного документа с вехами ЖЦ
- [ ] Process/Uncertainty leads to: 
- pure sprints with architecture DoD or
- RUP-like increments within phases and architecture stabilisation or
- Sequential process with up-front strict phases and may be iterations not sprints

Что определяет архитектурные решения (1/0.5)
-------------------------------------
- [ ] Ревью входных ограничений для архитектуры:
- Корпоративные архитектурные ограничения
- Проектные архитектурные ограничения
- IT-ландшафт, куда будет встраиваться система
- Функциональные и нефункциональные требования к системе
- Инфраструктура разработки, тестирования, эксплуатации
- [ ] Почему такая последовательность приоритетов?
- [ ] Но так же ограничения формируются _внутри_ команды _в процессе_ производства:
- Атрибуты внутренней модели качества
- Архитектурные гайдлайны/соглашения
- [ ] Продолжаем Шаблон архитектурного документа
- обоснуйте добавленные атрибуты внутренней модели качества

Требования как архитектурно значимый артефакт (1/0.5)
----------------------------------------------
- [ ] Даны требования к системе:
- FR в формате User Story / Job Story
- NFR в формате атрибутов качества
- Доменная модель в формате UML-диаграммы классов
- [ ] Какие ожидания архитектор предъявит к этим требованиям для снижения рисков реализации: 
- обеспечения корректности,
- борьбы со сложностью, 
- параллельности работ, 
- обеспечения гибкости и других внутренних атрибутов качества.
- [ ] Понятие типовых профилей требований
- типовые риски реализации
- [ ] Продолжаем Шаблон архитектурного документа
- отразить ожидания к требованиям
- отразить свои типовые профили «требования - риски»

Ключевая проблема инженерии #2: противоречивость требований (1/0.5)
------------------------------------------------------------
- [ ] Проблема #1 – неполнота, но это out of scope
- [ ] Основные конфликты и важность в – NFRs (Attribute Driven Design, ADD)
- [ ] Примеры конфликтов характеристик
- [ ] Суть инженерии как работа в условиях конфликта характеристик
- [ ] Trade-off как основная деятельность архитектора (Architecture Tradeoff Analysis Method, ATAM)
- [ ] Приоритезация требований как ключ к trade-offs
- [ ] Как можно по-другому решить?
- Принцип спецализации
- Компромисс
- [ ] Продолжаем Шаблон архитектурного документа
- документирование trade-off и причин решений

Ключевая проблема инженерии #3: неопределённость реализации (1/0.5) 
------------------------------------------------------------
- [ ] В зависимости от степени неопределенности:
- готовое оптимальное решение (best practice)
- анализ + паттерны (good practices)
- покупка в проект внешней экспертизы
- гипотезы + прототипы
- [ ] Продолжаем Шаблон архитектурного документа
- документирование решения
- документирование архитектурных прототипов

Ключевая проблема инженерии #4: изменчивость реализации (1/0.5)
--------------------------------------------------------
- [ ] Как обеспечить гибкость и параллельную разработку? Инкапсуляция
- [ ] Модули/Функции vs Компоненты/Реализации
- [ ] Практики функционального анализа и проектирования:
- модули -> контракты -> инкапсуляция в компоненты
- [ ] Trade-off: Suite или Best of breed?
- [ ] Продолжаем Шаблон архитектурного документа

Ключевая проблема инженерии #5: сложность реализации (3/0.5)
------------------------------------------------------
- [ ] Как снизить риски разработки больших и сложных систем?
- [ ] Декомпозиция
- [ ] Документация
- [ ] PoV
- почему структурная декомпозиция так важна?
- PoV: как увидеть решения за диаграммами 
- разбор ключевых PoV и скрытых в них атрибутов качества
