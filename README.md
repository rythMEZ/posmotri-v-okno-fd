# Посмотри в окно

Одностраничное веб-приложение для просмотра коротких видео с видами разных городов. Пользователь может отфильтровать подборку по городу и времени суток, выбрать ролик из списка и сразу воспроизвести его в основном плеере.

Проект выполнен на чистом HTML, CSS и JavaScript без UI-фреймворков и сборщика. Данные и медиафайлы загружаются из внешнего REST API.


## Стек

- HTML5
- CSS3
- JavaScript с `async/await`
- Fetch API
- HTML `<template>` для динамического создания карточек
- Stylelint
- Prettier
- Git и GitHub Actions


## Структура проекта

```text
.
├── .github/
│   └── workflows/
│       └── tests.yml
├── fonts/
│   ├── fonts.css
│   └── локальные шрифты
├── scripts/
│   └── script.js
├── styles/
│   ├── error.css
│   ├── preloader.css
│   └── style.css
├── index.html
├── package.json
└── stylelint.config.js
```
