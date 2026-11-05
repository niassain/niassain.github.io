# Сайт-визитка Никиты Шляпочника

Статический сайт: один `index.html` + папки `docs/` (PDF) и `assets/` (картинки). Никаких сборок и серверов не нужно.

## Бесплатный хостинг на GitHub Pages (5 минут, один раз)

1. На github.com создай новый **публичный** репозиторий, например `niassain/niassain.github.io`
   (если имя репозитория = `niassain.github.io`, сайт будет по адресу `https://niassain.github.io/`).
2. Загрузи в него всё содержимое этой папки (index.html, docs/, assets/, .nojekyll): кнопка **Add file → Upload files**, перетащи файлы, **Commit**.
3. Settings → Pages → Source: **Deploy from a branch**, Branch: **main**, папка **/ (root)** → Save.
4. Через 1–2 минуты сайт открывается по адресу `https://niassain.github.io/`.

Обновить сайт = заменить файлы в репозитории.

### Через терминал (если удобнее)
```bash
cd <эта папка>
git init && git add . && git commit -m "site"
git branch -M main
git remote add origin git@github.com:niassain/niassain.github.io.git
git push -u origin main
```

## Альтернативы (тоже бесплатно, без своих устройств)
- **Netlify Drop** (app.netlify.com/drop): перетащить папку в браузере — сайт готов сразу, адрес вида `имя.netlify.app`.
- **Cloudflare Pages**: то же через загрузку папки.

## Свой домен
В настройках GitHub Pages указать домен (например `shlyapochnik.ru`) и добавить CNAME-запись у регистратора на `niassain.github.io`.
