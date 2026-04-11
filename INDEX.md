# Словарь терминов программирования

Персональный словарь терминов и концепций из программирования, архитектуры и эксплуатации систем.

## Как пользоваться
- `INDEX.md` — главная навигация по темам.
- В каждом файле темы сначала идет краткий список терминов и определений.
- Ниже в этом же файле идут подробные карточки терминов: полное определение, назначение, ограничения, примеры и связанные понятия.
- Темы можно постепенно расширять без изменения общей структуры.

## Оглавление по темам

### 1. Architecture
Архитектурные и проектировочные термины: слои, зависимости, bounded context, CQRS, event sourcing, coupling, cohesion.

Файл: `topics/architecture.md`

### 2. OOP
Объектно-ориентированные концепции: инкапсуляция, наследование, композиция, полиморфизм, интерфейсы, контракты.

Файл: `topics/oop.md`

### 3. Functional
Функциональные идеи и приемы: чистые функции, immutability, closures, higher-order functions, currying, lazy evaluation.

Файл: `topics/functional.md`

### 4. Runtime and Memory
Память и выполнение программы: stack, heap, GC, ссылки, указатели, RAII, утечки памяти, boxing/unboxing.

Файл: `topics/runtime-memory.md`

### 5. Concurrency
Конкурентность, параллелизм и синхронизация: threads, async/await, channels, mutex, semaphore, race condition, deadlock.

Файл: `topics/concurrency.md`

### 6. Algorithms and Data Structures
Алгоритмы и структуры данных: массивы, списки, деревья, графы, хеш-таблицы, сложность, Big O, рекурсия, динамическое программирование.

Файл: `topics/algorithms-ds.md`

### 7. Databases
Базы данных и транзакционность: ACID, isolation levels, indexes, joins, migrations, ORM, optimistic/pessimistic locking.

Файл: `topics/databases.md`

### 8. Networking
Сети, API и распределенные системы: REST, gRPC, WebSocket, idempotency, retries, timeouts, consistency, replication.

Файл: `topics/networking.md`

### 9. Compilers and Languages
Устройство языков и компиляторов: lexer, parser, AST, IR, JIT, AOT, reflection, macros, metaprogramming.

Файл: `topics/compilers-languages.md`

### 10. Testing
Подходы к тестированию и качеству: unit, integration, e2e, mocks, stubs, fixtures, property-based testing, regression.

Файл: `topics/testing.md`

### 11. DevOps
Сборка, доставка и эксплуатация: CI/CD, artifacts, deploy, rollback, canary, blue-green, health checks, observability.

Файл: `topics/devops.md`

### 12. Security
Практические термины безопасности: authentication, authorization, hashing, encryption, tokens, secrets, least privilege, audit trail.

Файл: `topics/security.md`

## Порядок заполнения
Рекомендуемая последовательность итераций:
1. `topics/architecture.md`
2. `topics/oop.md`
3. `topics/functional.md`
4. `topics/runtime-memory.md`
5. `topics/concurrency.md`
6. `topics/algorithms-ds.md`
7. `topics/databases.md`
8. `topics/networking.md`
9. `topics/compilers-languages.md`
10. `topics/testing.md`
11. `topics/devops.md`
12. `topics/security.md`

## Правила оформления термина
Для единообразия каждая карточка термина должна содержать:
- **Кратко**
- **Полное определение**
- **Назначение / зачем это нужно**
- **Когда применять**
- **Ограничения / частые ошибки**
- **Примеры**
- **Связанные термины**

Шаблон темы: `topics/_template.md`
