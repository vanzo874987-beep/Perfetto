# Perfetto — QA Documentation

**Проект:** Мобильное приложение + Web-админка для управления заказами и доставкой.
**Стек:** React Native, Ruby on Rails 7, PostgreSQL, Kafka, Redis, ClickHouse.
**Моя роль:** Manual QA Engineer (функциональное тестирование, API, написание документации).

## 📁 Структура репозитория

- `checklists/` — чек-листы (smoke, regression, acceptance)
- `test_cases/` — детальные тест-кейсы
- `bug_reports/` — оформленные баг-репорты
- `api_collections/` — Postman-коллекции
- `test_data/` — тестовые данные
- `sql/` — SQL-запросы для проверки БД

## 📊 Статус тестирования сборки 1.5.2-beta

- Smoke-тестирование: провалено (блокирующий баг BR-001)
- Подробнее: `checklists/smoke_checklist.md`