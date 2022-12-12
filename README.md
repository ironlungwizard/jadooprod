# Jadoo
## Цель проекта
Цель заключалась в изучении HTML и CSS, а также полноценному применению их на практике. 
## Результаты
В качестве примера для разработки был взят дизайн с сайте с бесплатными примерами лендингов, сверстанных в Figma.
В результате разработки был реализован desktop дизайн из образца, а также его адаптивная версия, сжимающаяся вплоть до разрешения с шириной 375px, после чего включается зум.
## Особенности
В процессе реализации проекта я столкнулся со следующими нюансами:
1. Несоответствие шрифтов и размеров в Figma - дизайн был подогнан с помощью плагина PerfectPixel.
2. Отсутствие дизайна адаптивной версии - адаптивная версия была задизайнена самостоятельно.
3. Неоптимизированность фильтра drop-shadow с устройствами на iOS.
## Стэк
Для разработки были использованы: библиотека React, препроцессор SCSS. Проект поднимался на nginx. SCSS компилировался с помощью Babel, а модули собирались с помощью Webpack. Продуктовая версия развернута в Docker с помощью nginx в режиме обратного прокси. 
## Результат
Ссылка на проект, опубликованный на сервере: http://bulliadigitalis.sytes.net/jadoo/
