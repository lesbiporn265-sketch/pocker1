# Pock — шесть игроков

Веб-игра, экспортированная из Construct.

## Играть онлайн

После включения GitHub Pages игра будет доступна по адресу, указанному в разделе **Deployments** репозитория.

## Локальный запуск

Для работы игры нужен HTTP-сервер — не открывайте `index.html` напрямую через `file://`.

```bash
python3 -m http.server 8000
```

После этого откройте [http://localhost:8000](http://localhost:8000).

## Состав

- `index.html` — главная страница игры;
- `scripts/`, `images/`, `icons/` — файлы Construct и игровые ресурсы;
- `sw.js`, `offline.json`, `appmanifest.json` — offline/PWA-поддержка.

## Публикация

Игра разворачивается через GitHub Pages из корня ветки `main`.
