# Концепты рилс для edsmart (грибной суп)

Статическая страница с тремя концептами вертикальных роликов (Reels/Shorts) для продукта **edsmart — грибной суп**.

## Структура проекта

- `index.html` — основная страница с описанием концептов и раскадровкой.
- `imgs/` — папка с изображениями и превью кадров, на которые ссылается `index.html`.

## Как запустить локально

1. Скопируйте папку с картинками:
   - перенесите `c:\Users\LOVKEY\Downloads\3d ED суп\imgs` в `d:\сайт\new-project\imgs`
   - структура должна получиться: `d:\сайт\new-project\imgs\...файлы картинок...`
2. Откройте `index.html` в браузере (двойной клик или «Открыть с помощью…» → браузер).

## Как выложить на GitHub

В PowerShell из папки проекта:

```powershell
cd "d:\сайт\new-project"
git add .
git commit -m "Добавить концепты рилс edsmart"
git branch -M main
git remote add origin https://github.com/<ваш-логин>/<ваш-репозиторий>.git
git push -u origin main
```

