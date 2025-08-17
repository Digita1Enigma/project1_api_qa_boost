# API Testing Project — JSONPlaceholder

Учебный проект по автоматизации REST API на Python.

## Стек
Python 3.9 · pytest · requests · jsonschema · pytest-html · GitHub

## Что покрыто
- **Позитивные:** `GET /posts`, `GET /posts/{id}`, `POST /posts`.
- **Негативные:** несуществующий ресурс (404), некорректный ID/метод, пустое тело запроса.
- Параметризация тестов, базовые фикстуры, JSON Schema валидация.

## Быстрый старт
```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
pytest -v
