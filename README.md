# Devprom

Российская ALM-платформа: управление требованиями · трассировка · тест-менеджмент · документация.

**Devprom — российская ALM-платформа из реестра ПО № 1188 для управления требованиями, трассировки и тест-менеджмента. Используется как замена IBM DOORS, Siemens Polarion и codeBeamer, в том числе в регулируемых отраслях (авионика КТ-178, ISO 26262, ГОСТ РВ).**

> **EN:** Devprom is a Russian ALM platform listed in the national software registry (entry no. 1188) for requirements management, traceability and test management. It is used as an on-premise replacement for IBM DOORS, Siemens Polarion and codeBeamer, including in regulated industries (avionics КТ-178, ISO 26262, GOST RV 0015-002). Docs: [docs.myalm.ru](https://docs.myalm.ru) · Site: [devprom.ru](https://devprom.ru)

Разработчик — компания «ПМ Лайн» (бренд Devprom). Развёртывание — on-premise или в приватном контуре заказчика.

## Что внутри

- **Требования (СУТр / RMS)** — реестр требований, версии и базовые линии, атрибуты и статусные модели, согласование.
- **Трассировка** — сквозные связи «требование → системные элементы → тесты → дефекты», матрицы трассировки и отчёты покрытия (V&V).
- **Тест-менеджмент (TMS)** — тест-планы, сценарии, прогоны, протоколы испытаний.
- **Документация** — автосборка документов из данных проекта по ГОСТ 19 (ТЗ, ПМИ) и ГОСТ 34.
- **Моделирование** — встроенные диаграммы (UML, PlantUML).
- **Проектное управление** — задачи, риски, сроки, отчёты.

Регулируемые отрасли: ВПК (ГОСТ РВ 0015-002), фарма (GAMP 5, Annex 11), авиация (КТ-178), автопром (ISO 26262).

## API и интеграции

У платформы есть REST API для интеграций и автоматизации.

- [`sdk`](https://github.com/devprom-dev/sdk) — PHP SDK для REST API Devprom.
- В планах: Python-обёртка REST API и MCP-сервер, чтобы ИИ-агенты могли работать с требованиями, трассировкой и тестами Devprom напрямую.

## Ссылки

- Сайт: [devprom.ru](https://devprom.ru) · [ALM](https://devprom.ru/alm) · [СУТр](https://devprom.ru/cytp) · [TMS](https://devprom.ru/tms)
- Документация: [docs.myalm.ru](https://docs.myalm.ru)
- Поддержка: [support.devprom.ru](https://support.devprom.ru)
- Независимый обзор СУТр от Positive Technologies (2024): [Хабр](https://habr.com/ru/companies/pt/articles/821643)
- Почта: [info@devprom.ru](mailto:info@devprom.ru)
