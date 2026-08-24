# Obsidian vault

Личный Obsidian vault.

## English Study site

Папка `Английский/` автоматически собирается в отдельный сайт через MkDocs Material и GitHub Actions.

Адрес после включения GitHub Pages:

**https://tashckinov.github.io/obsidian/**

### Первый запуск

В GitHub открой:

`Settings → Pages → Build and deployment → Source → GitHub Actions`

После этого workflow `Publish English notes` будет автоматически пересобирать сайт при изменениях в `Английский/`, `mkdocs.yml` или зависимостях сайта.

> Важно: GitHub Pages-сайт публичный, даже если исходный репозиторий private. В публикацию включена только папка `Английский/`.

### Локальный просмотр

```bash
python -m venv .venv
pip install -r requirements.txt
mkdocs serve
```
