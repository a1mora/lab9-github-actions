# Лабораторная работа 9 — GitHub Actions

Проект демонстрирует автоматический запуск модульных тестов Python при отправке изменений в GitHub.

## Состав проекта

- `calculator.py` — тестируемый модуль калькулятора.
- `test_calculator.py` — 19 проверок с использованием pytest.
- `requirements.txt` — зависимость pytest.
- `.github/workflows/run-tests.yml` — workflow GitHub Actions.

## Локальный запуск

```bash
python -m pip install -r requirements.txt
pytest -v
```

## Автоматический запуск

Workflow запускается при `push`, `pull_request`, а также вручную через вкладку Actions.
После загрузки проекта в GitHub откройте вкладку **Actions** и проверьте завершение workflow.
