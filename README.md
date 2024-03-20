# Welcome, dear Traveler

Ультимативное руководство по собеседованию для программиста Golang и не только. 

The Ultimate Interview Guide for a Golang Programmer and more.

# Путеводитель (Table of contents)

- Вопросы на собеседовании
  - Общие вопросы
  - Алгоритмиечские задачи
- Golang
  - Тулинг (Tools)
  - Модули и пакеты (Modules & Packages)
  - Шедулинг и горутины (Shedule & Goroutines)
  - Каналы и операции над нами (Channels)
  - Контексты (Contexts)
  - Массивы и слайсы (Arrays & Slices)
  - Карты (Maps)
  - Интерфейсы и структуры (Interfaces & Structs)
  - Ошибки и паники (Errors & Panics)
  - Отложенные вызовы (Deferer)
  - Примитивы сихронизации (Sync Primitives)
  - Устройство строк, работа со строками (Strings in Golang)
  - Сборщик мусора (Garbage Collector)
  - Тесты (Tests)
  - Преимущества и недостатки
- [Алгоритмы](./ALGORITHMS.md)
  - [Прежде чем начать, зачем мне изучать концепцию Big O?](./ALGORITHMS.md#прежде-чем-начать-зачем-мне-изучать-концепцию-big-o)
     - [Оценка сложности алгоритмов, или Что такое Big O.](./ALGORITHMS.md#оценка-сложности-алгоритмов-или-что-такое-big-o) 
  - [Сортировки](./ALGORITHMS.md#сортировки)
     - [Ложка теории](./ALGORITHMS.md#ложка-теории)
     - [Пузырьковая сортировка (Bubble sort)](./ALGORITHMS.md#1-пузырьковая-сортировка-bubble-sort)
     - [Сортировка вставками (Insertion sort)](./ALGORITHMS.md#2-сортировка-вставками-insertion-sort)
     - [Сортировка подсчетом (Counting Sort)](./ALGORITHMS.md#3-сортировка-подсчетом-counting-sort)
     - [Быстрая сортировка (Quick Sort)](./ALGORITHMS.md#4-быстрая-сортировка-quick-sort){:target="_blank"}
  - [Поиск](./ALGORITHMS.md#поиск)
- Дизайн (паттерны кода) (Code Patterns)
  - [Refactoring.Guru](https://refactoring.guru/design-patterns/go)
  - [Паттерны проектирования с примерами на Golang](https://github.com/AlexanderGrom/go-patterns)
- Дизайн (принципы) (Design Principes)
  - [SOLID](https://github.com/goavengers/go-principles?tab=readme-ov-file#solid)
  - [DRY](https://github.com/goavengers/go-principles?tab=readme-ov-file#dry)
  - [KISS](https://github.com/goavengers/go-principles?tab=readme-ov-file#kiss)
  - [YAGNI](https://github.com/goavengers/go-principles?tab=readme-ov-file#yagni)
  - ООП
     - [Что такое ООП (объектно-ориентированное программирование)?](https://www.youtube.com/watch?v=ChEdFh7Q-Vw&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2&index=43)
     - [Объектно-ориентированное программирование за 10 минут](https://www.youtube.com/watch?v=W2V1ZUceKBk)
  - [DDD](https://github.com/goavengers/go-principles?tab=readme-ov-file#ddd) 
- Системный дизайн (System Design)
  - Кеширование
    - Redis
    - Memcached 
  - Балансировка нагрузки
    - HaProxy 
  - Межсервисное взаимодействие: gRPC, REST vs RPC, WeebHook, WebSocket
    - [Что такое REST на самом деле?](https://www.youtube.com/watch?v=08-RlaLgWx4)
    - [Что такое gRPC и Protobuf?](https://www.youtube.com/watch?v=_EqVG-El5z0)
    - WeebHook
       - [Что такое Webhook и чем отличается от API?](https://www.youtube.com/watch?v=KhuZdeuF6kw)
       - [Что такое Webhook за 12 минут](https://www.youtube.com/watch?v=_NlHzAaLH4g)
    - WebSockets
       - [Все про WebSockets (веб-сокеты) простыми словами](https://www.youtube.com/watch?v=19d4AXt3dSI&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2&index=40)
       - [Что такое веб-сокеты за 4 минуты](https://www.youtube.com/watch?v=WtF-wMzPtuM)
  - Брокеры сообщений
    - Apache Kafka
      - [Про Kafka (основы)](https://www.youtube.com/watch?v=-AZOi3kP9Js)
      - [Что такое Apache Kafka за 5 минут](https://www.youtube.com/watch?v=Mw9YFay8-WM)
    - RabbitMQ
      - [Основы RabbitMQ: что это и как это работает!](https://www.youtube.com/watch?v=i-Eh-NCa0Tk)
      - [Что такое RabbitMQ и чем он отличается от Apache Kafka за 10 минут](https://www.youtube.com/watch?v=w_M6WEGS2fw)
    - Nats
  - Микросервисы:
    - [Про микросервисы за 8 минут](https://www.youtube.com/watch?v=rCbdQc42eCw)
    - [Проблема транзакций в микросервисной архитектуре / Краткая теория ACID / Что такое транзакция](https://www.youtube.com/watch?v=oirgmpk8KSo) 
- Структуры данных (Data Steructures)
  - Массивы
  - Динамические массивы
  - Деревья
  - Графы
  - Боры (в сущности, это тоже деревья, но их целесообразно рассмотреть отдельно).
  - Хеш-таблицы
  - [Стек (Stack)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D1%81%D1%82%D0%B5%D0%BA)
  - [Очередь (Queue)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D0%BE%D1%87%D0%B5%D1%80%D0%B5%D0%B4%D1%8C)
  - [Множества (Set)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%B0-sets)
  - [Связанный список (Linked List)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D1%81%D0%B2%D1%8F%D0%B7%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5-%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D0%B8-linked-list)
- База данных
  - Реляционные базы
  - NoSQL базы 
- Инфраструктура, (Infrastructure, DevOps)
  - Docker
  - Kubernetes
  - Git & GitFlow
  - Ansible
  - Метрики, Мониторинг, Алертинг, Логи, Трейсы
    - Grafana
    - Prometheus
    - Graylog
    - Jaeger
  - CI/CD
    - Jetkins
    - DroneCI
    - TeamCity
    - GitLab, Bitbucket, Github Actions
- Сети (Networks)
  - [Что такое IP - адрес и можно ли по нему кого-то вычислить?](https://www.youtube.com/watch?v=6tFGoiok0u8)
  - [Модель OSI | 7 уровней за 7 минут](https://www.youtube.com/watch?v=je0QFU7p5Oo)
  - [Ethernet на пальцах](https://www.youtube.com/watch?v=jLGadArowCE)
  - [Маршрутизатор. Коммутатор. Хаб. Что это и в чем разница?](https://www.youtube.com/watch?v=Bwg-om5NnmQ)
  - [DNS сервер - что это и как работает?](https://www.youtube.com/watch?v=t2NMbSarXC4)
  - [Все, что вам нужно знать про DHCP](https://www.youtube.com/watch?v=XPRYaGCkXJ8)
  - [TCP и UDP | Что это такое и в чем разница?](https://www.youtube.com/watch?v=yMSJKBQINAc)
  - [Что такое TCP/IP: Объясняем на пальцах](https://www.youtube.com/watch?v=2I1HnSN1H9o)
  - [HTTP или HTTPS – как работает и в чем разница?](https://www.youtube.com/watch?v=C9T_7D12URI)
  - [Протокол OSPF (Open Shortest Path First) за 8 минут](https://www.youtube.com/watch?v=3TF9KxpetUw)
  - [SSL и TLS - в чем разница?](https://www.youtube.com/watch?v=OmlkEhRHRTA)
  - [Учим основы - что такое VLAN?](https://www.youtube.com/watch?v=tbg1JiTRBSQ)
  - [Основы BGP за 7 минут](https://www.youtube.com/watch?v=EVYagz5ZeiA&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2)
- Система (System, Linux)
  - [Про Linux за 5 минут | Что это или как финский студент перевернул мир?](https://www.youtube.com/watch?v=t2iMS8V8v_U&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2&index=5)
  - [RAID 0, 1, 5 и 10 | Что это?](https://www.youtube.com/watch?v=7pU3edBVcYw&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2&index=12)
  - [Как работает компьютерная память: что такое RAM, ROM, SSD, HDD и в чем разница?](https://www.youtube.com/watch?v=tjbB2vh627s&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2&index=33)
- [Топ 35 вопросов на собеседовании IT - спецу | Что тебя ждет и как отвечать, чтобы получить оффер?](https://www.youtube.com/watch?v=z0wDQc_UE2M&list=PLVULwBUtsriM4vvqL6HNAdkLMEo0NR3S2&index=35)

## Вопросы на собеседовании

- [Общие вопросы](#)
- [Алгоритмиечские задачи](#)

## Golang

### Тулинг (Tools)

-

### Модули и пакеты (Modules & Packages)

-

### Шедулинг и горутины (Shedule & Goroutines)

-

### Каналы и операции над нами (Channels)

- [Как на самом деле устроены каналы в Golang? | Golang channels internals](https://www.youtube.com/watch?v=ZTJcaP4G4JM)

### Контексты (Contexts)

-

### Массивы и слайсы (Arrays & Slices)

- [GoLang Slice в деталях, простым языком](https://www.youtube.com/watch?v=10LW7NROfOQ)

### Карты (Maps)

- [Хэш-таблицы за 10 минут](https://www.youtube.com/watch?v=0UX4MIfOMEs)
- [Как на самом деле устроен тип Map в Golang? | Golang под капотом](https://www.youtube.com/watch?v=P_SXTUiA-9Y)

### Интерфейсы и структуры (Interfaces & Structs)

- [Почему интерфейсы лучше размещать в месте использования - GoLang best practices](https://www.youtube.com/watch?v=eYHCCht8eX4)

### Ошибки и паники (Errors & Panics)

- 

### Отложенные вызовы (Deferer)

-

### Примитивы сихронизации (Sync Primitives)

-

### Устройство строк, работа со строками (Strings in Golang)

-

### Сборщик мусора (Garbage Collector)

-

### Тесты (Tests)

- [Генерация и использование моков в Go / Mockery](https://www.youtube.com/watch?v=qaaa3RsC0FQ)

### Преимущества и недостатки языка Golang относительно других популярных языков (Advantages and disadvantages of the Golang language)

-

## Дизайн (паттерны кода) (Code Patterns)

- [Refactoring.Guru](https://refactoring.guru/design-patterns/go)
- [Паттерны проектирования с примерами на Golang](https://github.com/AlexanderGrom/go-patterns)
- [SOLID](https://github.com/goavengers/go-principles?tab=readme-ov-file#solid)
- [DRY](https://github.com/goavengers/go-principles?tab=readme-ov-file#dry)
- [KISS](https://github.com/goavengers/go-principles?tab=readme-ov-file#kiss)
- [YAGNI](https://github.com/goavengers/go-principles?tab=readme-ov-file#yagni)
- OOP
- [DDD](https://github.com/goavengers/go-principles?tab=readme-ov-file#ddd)

## Структуры данных (Data Steructures)

Поскольку структуры данных используются для хранения информации в упорядоченном виде, а данные — самый важный феномен в информатике, истинная ценность структур данных очевидна.

Не важно, какую именно задачу вы решаете, так или иначе вам придется иметь дело с данными, будь то зарплата сотрудника, биржевые котировки, список продуктов для похода в магазин или обычный телефонный справочник.

В зависимости от конкретного сценария, данные нужно хранить в подходящем формате. У нас в распоряжении — ряд структур данных, обеспечивающих нас такими различными форматами.

##### Наиболее распространенные структуры данных

Сначала давайте перечислим наиболее распространенные структуры данных, а затем разберем каждую по очереди:

- Массивы
- Динамические массивы
- Деревья
- Графы
- Боры (в сущности, это тоже деревья, но их целесообразно рассмотреть отдельно).
- Хеш-таблицы
- [Стек (Stack)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D1%81%D1%82%D0%B5%D0%BA)
- [Очередь (Queue)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D0%BE%D1%87%D0%B5%D1%80%D0%B5%D0%B4%D1%8C)
- [Множества (Set)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%B0-sets)
- [Связанный список (Linked List)](https://github.com/goavengers/go-datastructure?tab=readme-ov-file#-point_right-%D1%81%D0%B2%D1%8F%D0%B7%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5-%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D0%B8-linked-list)

## Системный дизайн (System Design)

- Кеширование
- Балансировка нагрузки
- Межсервисное взаимодействие: gRPC, REST vs RPC, WeebHook, WebSocket
  - [Что такое REST на самом деле?](https://www.youtube.com/watch?v=08-RlaLgWx4)
  - [Что такое gRPC и Protobuf?](https://www.youtube.com/watch?v=_EqVG-El5z0)
  - [Что такое Webhook и чем отличается от API?](https://www.youtube.com/watch?v=KhuZdeuF6kw)
- Микросервисы:
  - [Про микросервисы за 8 минут](https://www.youtube.com/watch?v=rCbdQc42eCw)
  - [Проблема транзакций в микросервисной архитектуре / Краткая теория ACID / Что такое транзакция](https://www.youtube.com/watch?v=oirgmpk8KSo) 

## База данных

### Реляционные базы данных

**MicrosoftSQL Server, Oracle Database, MySQL, Postgres**

- Индексы
  - [Что такое SQL ИНДЕКСЫ за 10 минут: Объяснение с примерами](https://www.youtube.com/watch?v=LpEwssOYRKA&pp=ygUhcG9zdGdyZXMg0LLQtdGA0YHQuNC-0L3QvdC-0YHRgtGM)
  - [Базы данных. MySQL. Индексы](https://www.youtube.com/watch?v=RUF3n_EIcy8)
- Транзакции, уровни изоляции транзакций (ReadCommited, ReadCommited (default Postgres), RepeatableRead (default MySQL), Serializable)
  - [Базы данных. MySQL. Транзакции](https://www.youtube.com/watch?v=qb6l4B57Qmw)
  - [Уровни изоляции транзакций в базах данных](https://www.youtube.com/watch?v=dmjZTtoxyf4)
- ACID
  - [Что такое ACID за 9 минут](https://www.youtube.com/watch?v=vFmajCQ7Wuc)
- Репликация и шардирования
  - [Что такое ШАРДИНГ и РЕПЛИКАЦИЯ за 9 минут](https://www.youtube.com/watch?v=qdNlt8wR_84) 
- Запросы. Поиск и анализ проблем производительности запросов
- Postgres
  - Материалы:
    - [DEV1-12. 03. Изоляция и многоверсионность](https://www.youtube.com/watch?v=UTJAKhlJYT8)
    - [DEV1-12. 04. Буферный кеш и журнал](https://www.youtube.com/watch?v=oZdioVBV-fo)
  - Ключевые моменты
    - Буферный кеш
    - Жернал предзаписи (WAL)
    - Контрольная точка восстановления
    - Многоверсионность
    - Снимок данных
    - Блокировки
    - Очистка страниц
- MySQL
  - Типы движков: InnoDB и MyISAM
 
### NoSQL базы

- [NoSQL простым языком: что это и зачем нужно?](https://www.youtube.com/watch?v=IBzTDkYNB7I)
- [Что такое NoSQL за 6 минут](https://www.youtube.com/watch?v=Xu4S2OX8Gb4&t=281s)
  
- Типы баз данных:
  - **Key-Value** (Redis, Memcached, DynamoDB)
  - **Графовые** (Neo4j, Dgraph)
  - **Колончатые (столбцовые)** (Cassandra, HBase, Clickhouse)
  - **Документоориентированные** (MongoDB, Amazon DynamoDB, CouchDB)
  - **Поисковые БД** (ElasticSearch, Solr, Alglia)
  - **База данных временных рядов** (InfluxDB, Prometheus)
  - **Многомодульные БД** (пример Redis может и в графы и временные ряды и в документы)

## Инфраструктура, (Infrastructure, DevOps)

### Docker

- [Что такое Docker?](https://www.youtube.com/watch?v=aZTL2zRmOnA)

### Kubernetes

- [Что такое Kubernetes?](https://www.youtube.com/watch?v=klmpiHLSuXA)

### Метрики, Мониторинг, Алертинг

### Git & GitFlow

- [Что такое Git за 8 минут: Объясняем на пальцах](https://www.youtube.com/watch?v=G4f9OH4IQE8)
- [Что такое Git flow и когда использовать?](https://www.youtube.com/watch?v=umiT0yIsSrc)

### Ansible

- [Что такое Ansible?](https://www.youtube.com/watch?v=23Zec3ORJOY)
  
### CI/CD

- [Про CI/CD за 5 минут](https://www.youtube.com/watch?v=Y-hYifHkjMs)
- [Что такое Jenkins?](https://www.youtube.com/watch?v=CtHcrmRplJI)

## Сети (Networks)

