# QA Helper — Minified build repository

Ukrainian (Українська)

Цей репозиторій містить лише мінімізовану збірку скрипта для Tampermonkey: `qa-helper.js`.

## Швидка інструкція зі встановлення

1. Встановіть розширення Tampermonkey (Chrome/Edge/Firefox/Opera).
2. Відкрийте цей файл у «raw» вигляді в GitHub (або перейдіть за прямою URL до файлу). Приклад raw URL:

   https://raw.githubusercontent.com/zheka-yarynych/qa-helper-dev/main/qa-helper.js

3. Tampermonkey повинен автоматично показати кнопку «Install» при відкритті raw-файлу — натисніть її, щоб встановити скрипт.

Альтернатива — вручну в Tampermonkey:

- Відкрийте панель Tampermonkey → Dashboard → Utilities → Install from URL і вставте raw URL, або
- Dashboard → Add new script → видаліть шаблон → вставте вміст `qa-helper.js` і «Save».

## Оновлення скрипта

1. Автор публікує нову версію (оновлює мінімізований `qa-helper.js` у цьому репозиторії) і підвищує `@version` у метаданих скрипта.
2. Tampermonkey перевіряє оновлення автоматично (зазвичай кожні кілька годин). Щоб негайно отримати оновлення, відкрийте Tampermonkey Dashboard → Installed userscripts → знайдіть `QA Report Helper` → натисніть кнопку `Check for userscript updates` або використайте кнопку `Update`.

Якщо оновлення не застосувалось — можна перевстановити скрипт вручну через raw URL або очистити кеш Tampermonkey та перевірити ще раз.

## Примітки з безпеки

- Переконайтесь, що файл походить з надійного джерела (офіційного репозиторію). Мінімізований файл важко читати — при сумніві краще порівняти хеш або попросити відкритий оригінал.

---

This repository contains only the minified build of the Tampermonkey userscript: `qa-helper.js`.

## Quick install

1. Install Tampermonkey extension (Chrome/Edge/Firefox/Opera).
2. Open the raw file URL in your browser. Example raw URL:

   https://raw.githubusercontent.com/zheka-yarynych/qa-helper-dev/main/qa-helper.js

3. Tampermonkey should show an "Install" button when you open the raw file — click it to install the script.

Alternative manual install via Tampermonkey dashboard:

- Tampermonkey Dashboard → Utilities → Install from URL → paste the raw URL, or
- Dashboard → Add new script → remove template → paste the content of `qa-helper.js` → Save.

## Updating the script

1. The repository owner publishes a new minified `qa-helper.js` and bumps the `@version` value in the script header.
2. Tampermonkey checks for updates automatically. To force an immediate update: open Tampermonkey Dashboard → Installed userscripts → find `QA Report Helper` → click `Check for userscript updates` (or `Update`).

If update doesn't apply, reinstall from the raw URL or clear Tampermonkey cache and retry.
