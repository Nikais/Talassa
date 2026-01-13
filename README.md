# Talassa

## Запуск

Для запуска бэкенда необходимо иметь установленный poetry

```shell
cd backend && poetry install
poetry run uvicorn app.main:app --reload # Запуск бэкенд сервера
```

Проверка:
- http://127.0.0.1:8000/api/health
- http://127.0.0.1:8000/docs