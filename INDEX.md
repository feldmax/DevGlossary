# Словарь терминов программирования

Персональный словарь терминов и концепций из программирования, архитектуры, эксплуатации систем и инженерной практики.

## Статус

Базовый каркас словаря собран.

- Тем оформлено: **12**
- Шаблон темы: `topics/_template.md`
- Формат заполнения: **краткий список терминов + подробные карточки**

## Как пользоваться

- `INDEX.md` — главная навигация по словарю.
- В каждом файле темы сначала идет краткий список терминов и определений.
- Ниже в этом же файле идут подробные карточки терминов: полное определение, назначение, когда применять, ограничения, примеры и связанные понятия.
- Темы можно расширять без изменения общей структуры.
- При необходимости одну большую тему можно позже делить на подтемы без ломки оглавления.

## Оглавление по темам

### 1. [Architecture](topics/architecture.md)
Архитектурные и проектировочные термины: слои, зависимости, bounded context, CQRS, event sourcing, coupling, cohesion.

### 2. [OOP](topics/oop.md)
Объектно-ориентированные концепции: инкапсуляция, наследование, композиция, полиморфизм, интерфейсы, контракты.

### 3. [Functional](topics/functional.md)
Функциональные идеи и приемы: чистые функции, immutability, closures, higher-order functions, currying, lazy evaluation.

### 4. [Runtime and Memory](topics/runtime-memory.md)
Память и выполнение программы: runtime, stack, heap, GC, ссылки, указатели, RAII, утечки памяти, boxing/unboxing.

### 5. [Concurrency](topics/concurrency.md)
Конкурентность, параллелизм и синхронизация: threads, async/await, channels, mutex, semaphore, race condition, deadlock.

### 6. [Algorithms and Data Structures](topics/algorithms-ds.md)
Алгоритмы и структуры данных: массивы, списки, деревья, графы, хеш-таблицы, сложность, Big O, рекурсия, динамическое программирование.

### 7. [Databases](topics/databases.md)
Базы данных и транзакционность: ACID, isolation levels, indexes, joins, migrations, ORM, optimistic/pessimistic locking.

### 8. [Networking](topics/networking.md)
Сети, API и распределенные системы: TCP/UDP, HTTP, REST, gRPC, WebSocket, idempotency, retries, timeouts, consistency.

### 9. [Compilers and Languages](topics/compilers-languages.md)
Устройство языков и компиляторов: syntax, semantics, lexer, parser, AST, IR, JIT, AOT, reflection, macros, metaprogramming.

### 10. [Testing](topics/testing.md)
Подходы к тестированию и качеству: unit, integration, e2e, mocks, stubs, fixtures, flaky tests, property-based testing, regression.

### 11. [DevOps](topics/devops.md)
Сборка, доставка и эксплуатация: CI/CD, artifacts, deploy, rollback, canary, blue-green, health checks, observability.

### 12. [Security](topics/security.md)
Практические термины безопасности: authentication, authorization, hashing, encryption, tokens, secrets, least privilege, audit trail.

## Структура каталога

```text
programming-glossary/
├─ INDEX.md
└─ topics/
   ├─ _template.md
   ├─ architecture.md
   ├─ oop.md
   ├─ functional.md
   ├─ runtime-memory.md
   ├─ concurrency.md
   ├─ algorithms-ds.md
   ├─ databases.md
   ├─ networking.md
   ├─ compilers-languages.md
   ├─ testing.md
   ├─ devops.md
   └─ security.md
```

## Правила оформления термина

Для единообразия каждая карточка термина должна содержать:

- **Кратко**
- **Полное определение**
- **Назначение / зачем это нужно**
- **Когда применять**
- **Ограничения / частые ошибки**
- **Примеры**
- **Связанные термины**

Шаблон темы: [topics/_template.md](topics/_template.md)

## Принципы ведения словаря

- Формулировки должны быть короткими, точными и без лишней академической воды.
- Определения должны быть инженерно полезными, а не только формально правильными.
- Примеры должны показывать, где термин встречается в реальной разработке.
- Связанные термины должны помогать переходить по смысловым связям между темами.
- При добавлении новых терминов лучше сохранять существующий стиль, а не смешивать разные уровни детализации.

## Что можно делать дальше

Следующие логичные улучшения:

1. Пройтись по всем темам и выровнять перекрестные ссылки между терминами.
2. Добавить в каждую тему блоки «Часто путают с» и «Как распознать на практике».
3. Разделить крупные темы на более узкие, если они начнут разрастаться.
4. Позже собрать из Markdown отдельную читабельную версию в `docx` или `pdf`.
