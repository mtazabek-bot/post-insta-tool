# Сторонние компоненты

## Шрифты

Оба шрифта вшиты в `index.html` как data-URI (woff2) при сборке `build_tool.py`.
Получены из Google Fonts: `fonts.googleapis.com/css2` → файлы с `fonts.gstatic.com`.

| Шрифт | Начертания | Правообладатель | Лицензия |
|---|---|---|---|
| Arsenal | 400, 700, 400 italic | Andrij Shevchenko | SIL Open Font License 1.1 |
| JetBrains Mono | 400, 700 | JetBrains s.r.o. | SIL Open Font License 1.1 |

Текст лицензии: <https://openfontlicense.org/open-font-license-official-text/>
Источники: <https://fonts.google.com/specimen/Arsenal>, <https://fonts.google.com/specimen/JetBrains+Mono>

OFL разрешает встраивание и распространение шрифтов вместе с этим файлом,
в том числе в составе веб-страницы. Шрифты не переименованы и не изменены.

## Иконки и графика

Все иконки и элементы графики (объект `ICONS` внутри `index.src.html`) нарисованы
для этого инструмента, сторонних SVG в файле нет.

## Код

Внешних библиотек нет: разбор текста, отрисовка на canvas, кроп фотографий,
экспорт PNG и упаковка zip написаны в самом файле. Ни одной ссылки на внешний хост —
страница целиком работает офлайн.
