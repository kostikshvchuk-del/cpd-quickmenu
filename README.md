# CPD QuickMenu Generator

Генератор `quickmenu_data.json` для полицейского QuickMenu на RPM-ROLEPLAY (CPD).
Отделён в отдельный репозиторий из проекта [RPM-Police](https://github.com/kostikshvchuk-del/RPM-Police).

## Что внутри

| Файл | Назначение |
|------|------------|
| `index.html` | Сам генератор (форма → JSON, копирование и скачивание `quickmenu_data.json`) |
| `fonts/minecraft-rus.woff2`, `.woff` | Шрифт **Minecraft Rus** — пиксельный шрифт в стиле Minecraft с полной поддержкой кириллицы |
| `cpd.ahk` | AutoHotkey-скрипт с горячими клавишами для QuickMenu |

## Сайт

https://kostikshvchuk-del.github.io/cpd-quickmenu/

## Как пользоваться

1. Заполнить имя, должность, отдел, дату выдачи и подписи.
2. Нажать **«Сгенерировать и скопировать»** — JSON попадёт в буфер обмена.
3. Вставить содержимое в файл `quickmenu_data.json` в папке с клиентом Minecraft
   (или нажать **«Скачать quickmenu_data.json»**).

## Шрифт

Шрифт подключён локально через `@font-face` (`fonts/minecraft-rus.woff2`), без внешних
CDN — страница работает офлайн и не зависит от сторонних сервисов.
