
# RTSP-Catalog (GitHub Pages)

## Что внутри
- index.html — основная HTML-страница
- data.json — список RTSP-ссылок
- всё работает без eval, только через fetch

## Как опубликовать
1. Создай репозиторий на GitHub
2. Загрузи index.html и data.json в корень
3. Зайди в Settings → Pages:
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
4. Открой по ссылке: https://<имя>.github.io/<репозиторий>/
