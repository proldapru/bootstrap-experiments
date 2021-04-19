# Инструменты для работы с церковнославянскими текстами
Одностраничное web-приложение для упрощения изучения и вёрстки текстов на церковнославянском языке

[Попробовать](https://rawgit.com/proldapru/bootstrap-experiments/main/cu-tools/)

## Функционал
- Изучение Unocode-кодов текста с подсветкой специальных символов.
- Таблицы букв ЦС азбуки с диакритическими символами, с возможностью простого копирования (по клику) сочетаний Unicode-символов и HTML-кодов символов в буфер обмена.

## Эксперименты
### Bootstrap
- Accordion.
- Tables.
- Alerts.
- Toasts.
- Forms: Input group: input+button.
- Utilities: Text: .fs-3, .fs-5, .text-break.
- Utilities: Background: .bg-success.bg-gradient.
- Utilities: Position: .position-fixed, .top-0, .end-0.
- Utilities: Spacing: .p-3, .pb-0, .py-3, .m-3, .mb-3.

### jQuery
- Получение массива содержимого всех отобранных элементов с помощью сочетания методов map() и get().

### Clipboard.js
- Инициализация двух экземпляров класса ClipboardJS с разным функционалом.
- Обрабока события .on('success') с выдачей сообщения в Bootstrap.Toast.

### HTML
- Тег &lt;abbr&gt;.

### JavaScript
- Работа со шаблонными строками, в том числе вложенными шаблонами.
- String.indexOf() с побитовым НЕ (~).
- Стрелочные функции внутри Array.map(val, index).

### CSS
- Свойство user-select:none;


## Ссылки

### Об ЦС азбуке и её кодировании в Unicode
[Chur Slavonic Typography in Unicode, Unicode Technical Note #41 (pdf)](https://www.unicode.org/notes/tn41/tn41-1.pdf)

[Церковнославянский язык (Википедия)](https://ru.wikipedia.org/wiki/%D0%A6%D0%B5%D1%80%D0%BA%D0%BE%D0%B2%D0%BD%D0%BE%D1%81%D0%BB%D0%B0%D0%B2%D1%8F%D0%BD%D1%81%D0%BA%D0%B8%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA)

[Краткий учебник церковнославянского языка](http://wiki.orthodic.org/%D0%9A%D1%80%D0%B0%D1%82%D0%BA%D0%B8%D0%B9_%D1%83%D1%87%D0%B5%D0%B1%D0%BD%D0%B8%D0%BA_%D1%86%D0%B5%D1%80%D0%BA%D0%BE%D0%B2%D0%BD%D0%BE%D1%81%D0%BB%D0%B0%D0%B2%D1%8F%D0%BD%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_%D1%8F%D0%B7%D1%8B%D0%BA%D0%B0)

[Церковнославянский язык в таблицах](https://azbyka.ru/cerkovnoslavyanskij-yazyk-v-tablicax)

[Иследование Калашникова Ю.В. "Церковнославянская азбука" (pdf)](https://sancti.ru/sl/hs/intr-pre/cu/cu-pre-6.1.pdf)

### Шрифты
Unicode-шрифты Юрия Викторовича Калашникова Panteley 1.8 
https://sancti.ru/patr/soft/font/slavonic.htm

Unicode-шрифты от проекта "Славян­ская инфор­матика"
https://sci.ponomar.net/ru/fonts.html

8-битные шрифты от проекта "Ирмологий"
http://www.irmologion.ru/fonts.html

