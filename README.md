# Методичка 15 потока по веб-разработке

Короткий маршрут повторения фактически пройденных тем: HTML, CSS, Git, JavaScript, DOM, асинхронность, Fetch API и Webpack. Отдельный раздел помогает подготовиться к вопросам на техническом собеседовании.

## Локальный запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements-docs.txt
mkdocs serve
```

Откройте `http://127.0.0.1:8000`.

## Проверка перед публикацией

```bash
mkdocs build --strict
```

Сайт автоматически публикуется в GitHub Pages после отправки изменений в ветку `main`.
