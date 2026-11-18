# unit-integration-tests

Unit and integration tests (Jest) with GitHub Actions CI for QA/QC Lab 7.

## Структура проєкту
- `src/` — тестовані модулі (`math.js`, `auth.js`, `currency.js`, `api.js`)
- `tests/` — модульні та інтеграційні тести на базі Jest
- `.github/workflows/ci.yml` — конфігурація GitHub Actions для автоматичного запуску тестів

## Запуск тестів локально
```bash
npm install
npm test
```
