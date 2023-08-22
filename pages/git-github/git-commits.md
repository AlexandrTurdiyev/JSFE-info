# Git / GitHub - создание и оформление коммитов #
[На главную](../../README.md)
___

## Создание коммитов в Git, согласно документации и правилам RS School ##

### Требования к именам коммитов ###
- Названия коммитов должны быть согласно [гайдлайну](https://www.conventionalcommits.org/en/v1.0.0/)
- Тип коммита должен быть только в нижнием регистре (`feat`, `fix`, `refactor`, `docs` и т.д.)
- Должен использоваться present tense ("add feature" not "added feature")
    - present tense - настоящее время
        - add feature = добавить функцию
        - ~~added feature~~ = добавленная функция
- Должен использоваться imperative mood ("move cursor to..." not "moves cursor to...")

### Примеры коммитов ###
 - `init` - используется для начала проекта/таска. 
 Примеры: 
    - `init: start youtube-task` - init: запустить youtube-задачу
    - `init: start mentor-dashboard task` - init: запустить задачу mentor-dashboard

 - `feat:` - это реализованная новая функциональность из технического задания (добавил поддержку зумирования, добавил footer, добавил карточку продукта). 
 Примеры:
    - `feat: add basic page layout` - feat: добавить базовый макет страницы
    - `feat: implement search box` - feat: внедрить окно поиска
    - `feat: implement request to youtube API` - feat: реализовать запрос к youtube API
    - `feat: implement swipe for horizontal list` - feat: внедрить свайп для горизонтального списка
    - `feat: add additional navigation button` - feat: добавить дополнительную кнопку навигации
    - `feat: add banner` - feat: добавить баннер
    - `feat: add social links` - feat: добавить социальные ссылки
    - `feat: add physical security section` - feat: добавить раздел физической безопасности
    - `feat: add real social icons` - feat: добавить настоящие социальные иконки

- `fix:` - исправил ошибку в ранее реализованной функциональности. Примеры:
    - `fix: implement correct loading data from youtube` - реализовать правильную загрузку данных с youtube
    - `fix: change layout for video items to fix bugs` - изменить макет для видеоэлементов, чтобы исправить ошибки
    - `fix: relayout header for firefox` - заголовок relayout для firefox
    - `fix: adjust social links for mobile` - настроить социальные ссылки для мобильных устройств


- `refactor:` - новой функциональности не добавлял / поведения не менял. Файлы в другие места положил, удалил, добавил. Изменил форматирование кода (white-space, formatting, missing semi-colons, etc). Улучшил алгоритм, без изменения функциональности. 
Примеры:
    - `refactor: change structure of the project` - изменить структуру проекта
    - `refactor: rename vars for better readability` - переименовать vars для лучшей читабельности
    - `refactor: apply eslint` - применить eslint
    - `refactor: apply prettier` - применить красивее

- `docs:` - используется при работе с документацией/readme проекта. 
Примеры:
    - `docs: update readme with additional information` - обновить readme с дополнительной информацией
    - `docs: update description of run() method` - обновить описание метода run()
___

### Коммиты, которые использую я ###

- `init: start NAME project` - используется в качестве первого коммита в начале проекта.
- `feat: add basic page layout` - добавить базовый макет страницы.
- `feat(index.html): add header content`
- `feat: add burger menu` - добавить меню бургер.
- `feat(normilize.css): add and connect normilize.css` - добавить и подключить normilize.css.

___

### Информация о коммитах
- [Соглашение о коммитах](https://www.conventionalcommits.org/ru/v1.0.0/#specification)


- [](https://www.youtube.com/watch?v=WlIzoLK46is&t=128s)