# Псалтирь

Одностраничное web-приложение для чтения Псалтири

[Попробовать](https://rawgit.com/proldapru/bootstrap-experiments/main/psalter/)

## Эксперименты

### Bootstrap
- Navbar + fixed-top + collapsed panel. Скрытие collapsed panel методом hide().
- Form: form-check + form-switch.
- Form: form-select.
- Helpers: Text truncation: text-truncate.
- Utilities: Visibility: invisible.
- Utilities: Flex: d-flex + align-items-center (размещение логотипа).
- Utilities: Text: fs-4, lh-1 (текст в navbar-brand).

### jQuery
- Событие $(window).on('resize').
- Метод nextAll().

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

## Ссылки
### Тексты
Текст на церковнослявянском в Unicode взят отсюда: [Псалтирь в Библии с параллельным переводом](https://azbyka.ru/biblia/?Ps.1&utfcs), для сверки церковнославянского текста использованы [отсканированные тексты псалтири издательства Православного Свято-Тихоновского гуманитарного университета, Москва 2007](http://www.wco.ru/biblio/books/psalter/Main.htm).

Текст гражданским шрифтом взят отсюда: [Псалтирь гражданским шрифтом с ударениями и молитвами](https://azbyka.ru/molitvoslov/psaltir-po-kafizmam.html).

Текст Синодального перевода и параллельные места взяты отсюда: [Библия. Священное Писание Православной Церкви](https://sancti.ru/patr/hs/bible/22ps01.html).

### Другие ссылки
[Псалтирь на церковнославянском с параллельным переводом (синодальный)](http://wiki.orthodic.org/%D0%9F%D1%81%D0%B0%D0%BB%D1%82%D0%B8%D1%80%D1%8C) - псалмы набраны в [единой церковнославянской кодировке](http://irmologion.ru/ucsenc/ucslay8.html) (UCS).

[Псалтирь на церковнославянском языке](http://prav-book.ru/db/books/254/%D0%9F%D1%81%D0%B0%D0%BB%D1%82%D0%B8%D1%80%D1%8C%20%D0%BD%D0%B0%20%D1%86%D0%B5%D1%80%D0%BA%D0%BE%D0%B2%D0%BD%D0%BE-%D1%81%D0%BB%D0%B0%D0%B2%D1%8F%D0%BD%D1%81%D0%BA%D0%BE%D0%BC%20%D1%8F%D0%B7%D1%8B%D0%BA%D0%B5%20-%202010.pdf) (PDF), книга набрана в UCS.

[Псалтирь на греческом с подстрочным переводом на русский](https://manuscript-bible.ru/OT/Ps.html).

[Псалмы, употребляемые на Богослужениях](https://www.molitvoslov.com/text871.htm).

## TODO
Иконка приложения.

Мягкие переносы в текстах.

Усовершенствовать меню выбора псалмов.

В разделе "параллельные места" добавить расшифровку книг, для псалмов подгружать текст стиха.