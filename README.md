# Служебный репозиторий `alena-teacher.github.io`

Корневой сайт GitHub Pages для домена `https://alena-teacher.github.io/`.

Здесь лежит только то, что должно быть в корне домена:

- `robots.txt` — основной файл для поисковых роботов. Для project site
  `https://alena-teacher.github.io/services/` роботы читают robots.txt
  только из корня домена.
- `index.html` — редирект на основной сайт `/services/`.

Карта сайта находится в проекте `services`:

`https://alena-teacher.github.io/services/sitemap.xml`

## Публикация

1. Создать на GitHub пустой публичный репозиторий `alena-teacher.github.io`.
2. В настройках **Settings → Pages** выбрать **Deploy from a branch**,
   ветку `main` и папку `/(root)`.
3. Из этой папки выполнить:

```bash
git push -u origin main
```

После публикации проверить:

- `https://alena-teacher.github.io/robots.txt`
- `https://alena-teacher.github.io/` (должен вести на `/services/`)
