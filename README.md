# Negotiator Knowledge Base

Публичная библиотека переговорных методик для приватного ChatGPT-плагина **Negotiator**.

## Состав

- `knowledge/frameworks/batna.md` — BATNA и реальные альтернативы соглашению.
- `knowledge/frameworks/zopa.md` — зона возможного соглашения.
- `knowledge/frameworks/anchoring.md` — якорение и объективные ориентиры.
- `knowledge/frameworks/active-listening.md` — активное слушание.
- `knowledge/frameworks/concessions.md` — управление уступками.
- `knowledge/scenarios/price-negotiation.md` — тренировка ценовых переговоров.
- `knowledge/scenarios/salary-negotiation.md` — переговоры о зарплате.
- `knowledge/evaluation/scoring-rubric.md` — критерии доказательного разбора.
- `knowledge/manifest.json` — разрешённый список документов и метаданные.

## Подключение

Negotiator получает материалы по адресу:

`https://raw.githubusercontent.com/Rosemarin25/negotiator-knowledge/<COMMIT_SHA>/knowledge/manifest.json`

Приложение использует полный commit SHA, поэтому изменения библиотеки не влияют на рабочую версию до явного обновления ссылки.

## Правила обновления

1. Изменить или добавить Markdown-документ.
2. Обновить `knowledge/manifest.json`.
3. Проверить пути и содержимое.
4. Передать Negotiator новый полный commit SHA.

Не размещайте в репозитории приватные переговорные стенограммы, персональные данные, пароли и ключи доступа.

## Статус

Начальная версия: 8 учебных материалов. Язык: русский. Формат: Markdown + JSON manifest.
