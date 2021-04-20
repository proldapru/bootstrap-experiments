# Псалтырь

Одностраничное web-приложение для чтения Псалтыри

[Попробовать](https://rawgit.com/proldapru/bootstrap-experiments/main/psalter/)

## Эксперименты

### Bootstrap
- Navbar + fixed-top + toggler.
- Form: form-check + form-switch.
- Form: form-select.
- Helpers: Text truncation: text-truncate.
- Utilities: Visibility: invisible.

### jQuery
- Событие $(window).on('resize').

### HTML
- Тег &lt;abbr&gt;.

### CSS
- Работа со счётчиками в content псевдоэлемента ::before (counter-reset, counter-increment, counter()).
- Нестандартные маркеры списка в CSS-функции counter() (at-rule @counter-style).
- Позиционирование выносного (sup) элемента "внутри" строки: {vertical-align: text-top; font-size: x-small; line-height: .75;}.
- Вывод содержимого атрибута тега в content псевдоэлемента ::before (CSS-функция attr()).
- CSS-позиционирование псевдоэлемента ::before (position:relative у основного элемента, position:absolute у :: before).
- position:fixed для строки с заголовками столбцов.
- CSS-функция var() для {color: var(--bs-dark);}

## TODO
- расчёт ширины абзацев в разных колонках для отображения стихов на одном уровне.
