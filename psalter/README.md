# Псалтырь

Одностраничное web-приложение для чтения Псалтыри

[Попробовать](https://rawgit.com/proldapru/bootstrap-experiments/main/psalter/)

## Эксперименты

### Bootstrap
- Navbar + fixed-top + toggler.
- Form: form-check + form-switch.
- Form: form-select.
- Helpers: text-truncate.

### HTML
- Тег &lt;abbr&gt;.

### CSS
- Работа со счётчиками в content псевдоэлемента ::before (counter-reset, counter-increment, counter()).
- Нестандартные маркеры списка в CSS-функции counter() (at-rule @counter-style).
- Вывод содержимого атрибута тега в content псевдоэлемента ::before (CSS-функция attr()).
- CSS-позиционирование псевдоэлемента ::before (position:relative у основного элемента, position:absolute у :: before).
- position:fixed для строки с заголовками столбцов.

## TODO
- равномерная ширина абзацев текста с учётом выносных номеров (vertical-align: super).
- расчёт ширины абзацев в разных колонках для отображения стихов на одном уровне.
