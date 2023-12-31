## Неделя #1: Хостинг. Работа с путями. Разметка для Главной

Практика:
Создать в GitHub новый репозитории.
Склонировать его себе (инструкция появиться на странице после создания нового репозитория).
Написать разметку для Главной страницы проекта.
Загрузить в репозиторий новые созданные файлы.

### 🗓 Вторник
Установить VSCode
Посмотреть видео по работе с редактором VSCode
Подобрать комфортную для работы цветовую схему редактора =)

Установить скриншотер (желательно Яндекс.Диск)

### 🗓 Среда
Найти/почитать/посмотреть:
- какой-нибудь краткий курс "Как устроен (работает) Интернет"
- видео "Работа с GitHub Pages" (Важно, не путать Git и GitHub).

Практика:
Создать репозиторий для практики (название можно выбрать произвольно). Не для проекта. Потом его удалим.
Склонировать его себе (инструкция появиться на странице после создания нового репозитория).
Попробовать локально отредактировать README.md, сделать commit и залить его в репозиторий (push)

### 🗓 Четверг
Найти/почитать/посмотреть:
- Какой-нибудь вводный курс типа "HTML за час"

Создать файлы по следующей структуре

├─ folder  
│  └─ inner  
│     └─ index.html  
└─ img  
   ├─ img1.png  
   └─ img2.png  

#### Реализация  
В файл index.html вставить 2 картинки при помощи тега \<img>
Путь к первой картинке должен быть абсолютным, а ко второй - относительным
Также в файл вставить тег \<h1> и тег \<p> с произвольным содержанием

Загрузить файлы на GitHub Pages

#### Результат

ссылка на веб-ресурс вида: http://%имя-вашего-аккаунта%.github.io/%имя-проекта%/folder/inner

В котором отображены 2 картинки и текстовое содержание тегов \<h1> и тег \<p>
Картинки могут быть произвольные, формата jpg либо png

Стоит сразу взять себе за правило никогда не использовать в именах файлов и директорий следующие вещи:

Кириллицу
Пробелы
Буквы разных регистров
Транслит
Т.е. стараться называть файлы латинскими буквами, английским языком и в нижнем регистре (иногда некоторые соглашения в командах диктуют называть файлы с большой буквы, но это скорее - исключение). Если в имени несколько слов, то используйте знак нижнее подчеркивание "_", либо тире "-".
К примеру, название файла user-avatar-preview.jpg - отличное название, а
cartinka Dla-polZovatela11.png - не очень.

### 🗓 Пятница
Найти/почитать/посмотреть:
- БЭМ
https://ru.bem.info/methodology/quick-start/
для начала достаточно только страницы "Быстрый старт"

Создать новый репозиторий на GitHub, привязaть к нему GitHub Pages.
Склонировать себе и работать уже в нем. (Старый можно удалить)

Создать файл index.html, сделать коммит
например
git commit -m 'create index.html'
и загрузить в репозиторий GitHub.

Начинаем верстку.
Верстка всей страницы не лежит прямиком в \<body> , а должна быть обернута каким-либо блоком, например, тегом \<div> с классом .wrapper

Элементы, имеющие одну смысловую нагрузку и представленные несколькими экземплярами (меню, иконки соц. сетей и т.п ), размечаются в виде списка с использованием тегов \<ul> и \<li>

Элементы, отображающие информацию одного и того же типа, должны быть размечены идентично, т.е. разметка их элементов и их классы - совпадают

#### Результат
ссылка на главную страницу вида: http://%имя-вашего-акканута%.github.io/%имя-проекта/

HTML документ содержит разметку для главной страницы (теги и верные имена классов для них)

Обрати внимание

Главной страницей сайта считается та страница, на которую попадает пользователь после прохождения авторизации либо после перехода по ссылке из приветственной страницы, как правило, содержит важный для пользователя контент и остальные внутренние страницы похожи на нее по своей структуре.

Выполнить разметку страницы — создать в HTML-коде необходимые для последующей стилизации блоки, теги, и соответствующие имена классов к ним.

Пока без CSS
