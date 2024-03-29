# :man_student: Проектная работа "Научиться учиться"

Это типовой одностраничный информационный сайт. На котором отрабатываются навыки, полученные в ходе обучения на курсе ["Веб-разработчик"](https://practicum.yandex.ru/web/) в Яндекс.Практикуме. Для наполнения сайта выбран созвучный теме обучения материал. Верстая текст и картинки, я должен был познакомиться с методиками, полезными для повышения эффективности и осознанности на предстоящем учебном пути.

![learn](https://user-images.githubusercontent.com/97102815/229091852-0327ea7c-6b8a-4fd6-b9a6-c3f5a2e1c4dc.gif)

Это вторая часть проектой работы. В ней оттачивались навыки использования технологий **HTML5** и **СCS3**. Была создана структура по правилам **[Nested БЭМ](https://ru.bem.info/methodology/filestructure/#nested)**.

## Задачи проектной работы, что сделано и что предстоит сделать:
### :one: часть
- [x] использовать флексбокс-вёрстку
- [x] использовать позиционирование (относительное и абсолютное)
- [x] использовать продвинутую семантику языка HTML[^1]
- [x] проверить правильности отображения в разных браузерах[^2]
- [x] проверить код на валидность[^3]
- [x] создать кликабельные ссылки
- [x] прописать атрибут `alt` для изображений
- [x] соблюсти соответствие заголовков иерархии страницы
- [x] обнулить стандартные значения отступов у элементов
- [x] убедиться в  отсутствии фиксированной высоты у блоков
- [x] использовать только предложенные в брифе цвета
### :two: часть
- [x] переработать файловую структуру правилам Nested БЭМ[^4]
- [x] все файлы с картинками должны лежать в отдельной директории `images`
- [x] повторно использовать и модифицировать блоки
- [x] добавить ссылкам эфффект плавной прозрачности при наведении
- [x] добавить новые блоки
- [x] расположить старые и новые блоки в новом порядке
- [x] сделать сетку из карточек не используя `grid`
- [x] проверить код на валидность
- [x] реализовать анимацию вращения фоновых синих фигур через `@keyframes` в блоке `rotation`
- [x] вставить видео с помощью `iframe`
- [ ] подобрать и подключить шрифты из коллекции [Google Fonts](https://fonts.google.com/), чтобы получить отличный от других студентов проект
- [ ] добавить еще видео на тему образования с помощью API Youtube.
- [ ] добавить учебные подкасты используя API Яндекс Музыки.
- [ ] добавить кроссбраузерность и дописать вендорные префиксы.
- [ ] добавить форму обратной связи, чтобы пользователи смогли отправлять мне комментарии

[^1]: Использование элементов структурной семантики `<header>`, `<main>`, `<section>`, `<article>`, `<nav>` и `<footer>`.
[^2]: Firefox, Google Chrome и Yandex Browser.
[^3]: Проверка CSS — [CSS Validation Service](https://jigsaw.w3.org/css-validator/), проверка HTML — [Markup Validation Service](https://validator.w3.org/).
[^4]: Классическая схема организации файловой структуры БЭМ-проектов: блоку соответствует одна директория; код модификаторов и элементов находится в отдельных файлах;  файлы модификаторов и элементов хранятся в отдельных директориях; директория блока является корневой для поддиректорий его элементов и модификаторов; имена директорий элементов начинаются с двойного подчеркивания(__); имена директорий модификаторов начинаются с одинарного подчеркивания (_).
