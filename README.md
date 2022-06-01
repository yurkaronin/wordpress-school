# Создание темы для CMS WP

 Для начала создай папку в соответствующем разделе/
 Путь от корня сайта: /public_html/karaway_school/wp-content/themes/newtheme

Для того что бы тема отображалась в интерфейсе CMS необходимо создать два обязательных файла:

- style.css
- index.php

## Заполняем файл style.css

    /*
    Theme Name: New Theme
    Theme URI: http://karaway-school.ru/wordpress/themes/newtheme/
    Author: Yuriy Ronin
    Author http://karaway-school.ru/
    Description: "Учебная тема newtheme, созданная для демонстрации процесса разработки."
    Requires at least: 5.9
    Tested up to: 6.0
    Requires PHP: 7.4
    Version: 1
    License: #
    License URI: #
    Text Domain: newtheme
    Tags: clean & perfect :)
    */

Поздравляю.Теперь при экспорте папки с темой в соответствующий разрел WP система распознает новую тему и вы сможете активировать её в панели управления.

## Добавляем preview темы

Что бы тема смотрелась интересней добавим preview - это небольшое изображение размером 1200 на 900. В формате JPG.
Не забывайте что изображение не должно быть тяжёлым. Попробуйте подогнать под требуемый размер и оптимизировать по вес/качество.
Готовую картинку называем screenshot.jpg и готово.

Вы добавили preview в новую тему и теперь она достойно смотрится в панели управления.
Наша стартовая и чистая тема готова!