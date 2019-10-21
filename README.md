# Дипломная работа к профессии frontend-разработчик (Система бронирования ЖД билетов)

### Краткое описание задачи дипломной работы:
Создать SPA на React для сервиса покупки билетов на ж/д, сверстанное по [макетам в Figma](https://www.figma.com/file/7981GjEsjSpBUKolk4xFoT/%D0%97%D0%B0%D0%BA%D0%B0%D0%B7-%D0%B1%D0%B8%D0%BB%D0%B5%D1%82%D0%BE%D0%B2?node-id=0%3A1), в котором в качестве Апи используется [внешний сервер](https://netology-trainbooking.herokuapp.com/).

## План работ:
1.	Не паникуйте
1.	Внимательно рассмотрите [макетам в Figma](https://www.figma.com/file/7981GjEsjSpBUKolk4xFoT/%D0%97%D0%B0%D0%BA%D0%B0%D0%B7-%D0%B1%D0%B8%D0%BB%D0%B5%D1%82%D0%BE%D0%B2?node-id=0%3A1), определите для себя план вёрстки макетов, выделите  общие компоненты.
1.	Верстайте страницы придерживаясь  [правил именования по БЭМ](https://ru.bem.info/methodology/naming-convention/).
1.	[Создайте приложение React](https://github.com/facebook/create-react-app).
1.	Используя сверстанные ранее страницы, итеративно наполняйте ваше React-приложение функционалом.
1.	Проверьте, всё ли работает.
1.	Отправьте ссылку вашего проект на github или расшаренную папку дипломному руководителю на проверку.

В качестве заготовки можно взять https://bitbucket.org/sesdew/fe-git-example/src/master/ - это пустой репозиторий с прописанным .gitignore для проектов на react, 

"Заливайте" изменения на github или в файлообменник хотя бы раз в день (сгорит жесткий диск, пропадет ноутбук или из-за скачка напряжения все данные на ПК «самоудалятся», то всегда будет резервная копия с отставанием максимум в день).

## Что является итогом работы?
1.	Репозиторий на github с файлами вашего проекта

или

2.	Папка на Yandex/Google диске c файлами вашего проекта(без node_modules)

## Описание проекта


### Основные элементы

1. Вагон
1. Направление
1. Группа направлений
1. Место (билет)

### Вагон

1. Вагон может быть одним из типов: сидячий, люкс (СВ), купе, плацкарт
1. У каждого типа вагона своя карта рассадки мест.
1. У каждого вагона своя стоимость билетов.
1. Для каждого вагона есть возможность выбора дополнительных услуг: 
бельё, кондиционер и Wi-Fi.
1. Для некоторых вагонов стоимость белья включена в стоимость билета 
(стоимость белья не должна прибавляться при формировании конечной стоимости билета).

## Направление 

1. Направление - путь движения вагона из одного города в другой.
1. Направление предполагает движение поезда только в одну сторону.
1. Направление имеет дату отправления и дату прибытия.

АПИ-методы по работе с направлениями: [Смотреть тут](./api/routes.md)

## Группа направлений

1. Используется для того, чтобы обеспечить возможность
путешествия из одного города в другой и обратно.
1. Объединяет в себе два направления

## Место (билет)

1. Имеет свой номер на карте вагона
1. Может быть занято другим пассажиром
1. Закреплено за конкретным направлением


### Далее [Информация по API](./reference/api.md)

### Как правильно задавать вопросы дипломному руководителю?

**Что следует делать, чтобы все получилось:**

* Попробовать найти ответ сначала самому в интернете. Ведь, именно это скилл поиска ответов пригодится тебе на первой работе. И только после этого спрашивать дипломного руководителя
* В одном вопросе должна быть заложена одна проблема 
* По возможности, прикреплять к вопросу скриншоты и стрелочкой показывать где не получается. Программу для этого можно скачать здесь https://app.prntscr.com/ru/
* По возможности, задавать вопросы в комментариях к коду. 
* Начинать работу над дипломом как можно раньше! Чтобы было больше времени на правки. 
* Делать диплом по-частям, а не все сразу. Иначе, есть шанс, что нужно будет все переделывать :)  

**Что следует делать, чтобы ничего не получилось:**

* Писать вопросы вида “Ничего не работает. Не запускается. Всё сломалось.”
* Откладывать диплом на потом. 
* Ждать ответ на свой вопрос моментально. Дипломные руководители - работающие разработчики, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы! 
