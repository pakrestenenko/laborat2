---
# Front matter
lang: ru-RU
title: "отчёт по лабораторной работе номер 8"
subtitle: "Дисциплина: Операционные системы"
author: "Крестененко Полина Александровна НПМ бд 01-20"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander.Приобретение навыков практической работы по просмотру каталогов и файлов;манипуляций с ними

# Задание

Выполнить работу по заданным пунктам "Последовательность выполнения работы"

# Выполнение лабораторной работы

Задание 1:
1) Изучим информацию о mc, вызвав в командной строке «man mc»
Midnight Commander (или mc) − псевдографическая командная
оболочка для UNIX/Linux систем. Для запуска mc необходимо в
командной строке набрать «mc» и нажать «enter».(рис. -@fig:001)

![вызов mc](image/1.png){ #fig:001 width=70% }

(рис. -@fig:002)

![справка](image/2.png){ #fig:002 width=70% }

2) Запустим из командной строки mc и изучим его структуру и меню
(Рисунки 3-11).
В стандартном состояние окно редактора состоит из двух панелей(Рисунок 4).
Верхнее меню содержит меню «Левая панель», «Файл», «Команда»,
«Настройки», «Правая панель» (Рисунки 5-9).
Нажав клавиши «fn»+«F2», можно открыть «Меню пользователя»
(Рисунок 10).
Нажав клавиши «fn»+«F1», можно открыть «Помощь» (Рисунок 11).(рис. -@fig:003)

![вызов](image/3.png){ #fig:003 width=70% }

(рис. -@fig:004)

![командная оболочка](image/4.png){ #fig:004 width=70% }

(рис. -@fig:005)

![структура командной оболочки](image/5.png){ #fig:005 width=70% }

(рис. -@fig:006)

![структура командной оболочки](image/6.png){ #fig:006 width=70% }

(рис. -@fig:007)

![структура командной оболочки](image/7.png){ #fig:007 width=70% }

(рис. -@fig:008)

![структура командной оболочки](image/8.png){ #fig:008 width=70% }

(рис. -@fig:009)

![структура командной оболочки](image/9.png){ #fig:009 width=70% }

(рис. -@fig:010)

![меню пользователя](image/10.png){ #fig:010 width=70% }

(рис. -@fig:011)

![помощь](image/11.png){ #fig:011 width=70% }

3)Выполним несколько операций в mc,используя управляющие клавиши
выделение/отмена выделения файлов Используем клавишу«ins»(предварительно отключив ввод цифр с этой части клавиатуры ноутбука с помощью «numlock») и выделяем необходимые файлы(они выделяются желтым цветом)(рис. -@fig:012)

![выделение](image/12.png){ #fig:012 width=70% }

Для выделения файлов или его отмены можно использовать
также пункты «Отметить группу», «Снять отметку», «Обратить
выделение» в меню «Файл» (рис. -@fig:013)

![снятие выделения](image/13.png){ #fig:013 width=70% }

копирование/перемещение файлов
Для копирования файла используются клавиши «fn»+«F5»(рис. -@fig:014)

![копирование файлов](image/14.png){ #fig:014 width=70% }

Для перемещения файла используются клавиши «fn»+«F6».(рис. -@fig:015)

![перемещение файлов](image/15.png){ #fig:015 width=70% }

получение информации о размере и правах доступа на файлы
и/или каталоги
Для получения данной информации можно перейти в пункты:
«Левая панель» → «Информация» (рис. -@fig:016)

![левая панель](image/16.png){ #fig:016 width=70% }

(рис. -@fig:017)

![информация](image/17.png){ #fig:017 width=70% }

«Левая панель» → «Формат списка» → «Расширенный»(рис. -@fig:018)

![формат списка](image/18.png){ #fig:018 width=70% }

(рис. -@fig:019)

![расширенный](image/19.png){ #fig:019 width=70% }

«Файл» → «Права доступа» (рис. -@fig:020)

![права доступа](image/20.png){ #fig:020 width=70% }

«Файл» → «Права (расширенные)» (рис. -@fig:021)

![расширенные права](image/21.png){ #fig:021 width=70% }

4) Выполним основные команды меню правой панели 
Пункт «Список файлов» отображает размер файла и время его
правки(рис. -@fig:022)

![список файлов](image/22.png){ #fig:022 width=70% }

Пункт «Быстрый просмотр» необходим для предпросмотра
содержания файла(рис. -@fig:023)

![быстрый просмотр](image/23.png){ #fig:023 width=70% }

Пункт «Информация» отображает подробные данные о файле (рис. -@fig:024)

![информация](image/24.png){ #fig:024 width=70% }

Пункт «Дерево» необходим для просмотра дерева каталога
(отображает минимум информации)(рис. -@fig:025)

![дерево](image/25.png){ #fig:025 width=70% }

Пункт «Формат списка» − «Укороченный» отображает толькоимя файла или каталога (минимальная информация)(рис. -@fig:026)

![укороченный формат списка](image/26.png){ #fig:026 width=70% }

Пункт «Формат списка» − «Расширенный» отображает
подробную информацию о файлах, но менее подробную, чем
пункт «Информация»(рис. -@fig:027)

![расширенный формат списка](image/27.png){ #fig:027 width=70% }

Пункт «Формат списка» − «Определенный пользователем»
предоставляет пользователю возможность самому изменять
степень подробности информации о файле, но она будет менее
подробной, чем в пункте «Информация»

Пункт «Формат списка» − «Стандартный» ставится по
умолчанию

Пункт «Порядок сортировки» необходим для сортировки
файлов или каталогов по конкретному критерию(рис. -@fig:028)

![порядок сортировки](image/28.png){ #fig:028 width=70% }

Пункт «Фильтр» необходим, чтобы просматривать название
файлов или каталогов, которые подходят под указанную маску

5) Используя возможности подменю «Файл», выполним:

просмотр содержимого текстового файла
Выберем текстовый файл и перейдем в пункт «Просмотр»(рис. -@fig:029)

![просмотр](image/29.png){ #fig:029 width=70% }

редактирование содержимого текстового файла (без сохранения
результатов редактирования).Перейдем в пункт «Правка» и изменим первое слово(рис. -@fig:030)

![правка](image/30.png){ #fig:030 width=70% }

(рис. -@fig:031)

![правка](image/31.png){ #fig:031 width=70% }

создание каталога
Перейдем в пункт «Создание каталога»  и создадим
каталог abcd(рис. -@fig:032)

![создание каталога](image/32.png){ #fig:032 width=70% }

копирование файлов в созданный каталогДля этого, используя клавишу «ins», выделим несколько файлов.Затем выбрав пункт «Копирование», скопируем данные файлы
в созданный каталог (рис. -@fig:033)

![копирование](image/33.png){ #fig:033 width=70% }

6) С помощью соответствующих средств подменю «Команда» осуществим:

поиск в файловой системе файла с заданными условиями
Перейдем в пункт «Поиск файла» и зададим следующие
параметры: «От каталога» /, «Шаблон имени» *.с, «Содержимое» main  и дождемся окончания поиска(рис. -@fig:034)

![поиск файла](image/34.png){ #fig:034 width=70% } 

Аналогичным образом найдем файлы с шаблоном имени *.cpp (рис. -@fig:035)

![копирование](image/35.png){ #fig:035 width=70% }

выбор и повторение одной из предыдущих команд
Перейдем в пункт «История командной строки» и увидим, что
внизу экрана появилась сноска «История», но т.к. командная
строка не была использована эта сноска пустая (рис. -@fig:036)

![история](image/36.png){ #fig:036 width=70% }

переход в домашний каталог
Для перехода в домашний каталог перейдем в пункт «Дерево
каталогов», выберем необходимый каталог и нажмем «enter», в результате чего, в левой панели перейдем в домашний каталог (рис. -@fig:037)

![переход в домашний каталог](image/37.png){ #fig:037 width=70% }

(рис. -@fig:038)

![переход в домашний каталог](image/38.png){ #fig:038 width=70% }

анализ файла меню и файла расширений
Перейдем в пункт «Редактировать файл расширений» 
Редактировать файл расширений − позволяет задать с помощью определённого синтаксиса действия при запуске файлов с определённым расширением (например, какое программное обеспечение запускать для открытия или редактирования
файлов с расширением doc или docx).
Пункт«Редактировать файл меню» − позволяет
отредактировать контекстное меню пользователя(рис. -@fig:039)

![редактировать файл расширений](image/39.png){ #fig:039 width=70% }

(рис. -@fig:040)

![редактировать пользовательский файл меню](image/40.png){ #fig:040 width=70% }

7) Вызовем подменю «Настройки». Освоим операции,
определяющие структуру экрана mc:

Перейдем в пункт «Конфигурация».
Этот пункт позволяет скорректировать настройки работы с
панелями.(рис. -@fig:041)

![конфигурация](image/41.png){ #fig:041 width=70% }

Перейдем в пункт «Внешний вид», а затем в
пункт «Настройки панелей». Данные пункты определяют элементы (строка меню, командная
строка, подсказки и прочее), отображаемые при вызове mc, а
также геометрию расположения панелей и цветовыделение.(рис. -@fig:042)

![внешний вид](image/42.png){ #fig:042 width=70% }

(рис. -@fig:043)

![настройки панелей](image/43.png){ #fig:043 width=70% }

Перейдем в пункт «Подтверждение».
Этот пункт позволяет установить или убрать вывод окна с
запросом подтверждения действий при операциях удаления и
перезаписи файлов, а также при выходе из программы.(рис. -@fig:044)

![подтверждение](image/44.png){ #fig:044 width=70% }

Перейдем в пункт «Оформление».
Данный пункт позволяет поменять цветовую гамму визуальной
оболочки для комфортной работы.(рис. -@fig:045)

![оформление](image/45.png){ #fig:045 width=70% }

Перейдем в пункт «Биты символов». Этот пункт задаёт формат обработки информации локальным
терминалом.(рис. -@fig:046)

![биты символов](image/46.png){ #fig:046 width=70% }

Перейдем в пункт «Распознавание клавиш».Данное диалоговое окно используется для тестирования
функциональных клавиш, клавиш управления курсором и
прочее.(рис. -@fig:047)

![распознование клавиш](image/47.png){ #fig:047 width=70% }

Перейдем в пункт «Виртуальные ФС».Это настройки виртуальной файловой системы: тайм-аут,
пароль и прочее.(рис. -@fig:048)

![виртуальные ФС](image/48.png){ #fig:048 width=70% }

Перейдем в пункт «Сохранить настройки.Данный пункт сохранит все изменения.(рис. -@fig:049)

![сохранить настройки](image/49.png){ #fig:049 width=70% }

1) С помощью команды «touch text.txt» создаем текстовой файл text.txt.
Командой «ls» проверяем правильность выполненных действий.
Открываем этот файл с помощью встроенного mc редактора командой
«mcedit text.txt» (рис. -@fig:050)

![создание файла](image/50.png){ #fig:050 width=70% }

2) См. пункт выше.
3) Вставим в открытый файл небольшой скопированный из Интернета фрагмент текста (рис. -@fig:051)

![текст](image/51.png){ #fig:051 width=70% }

4)
Удалим 5-ю строку текста с помощью клавиш «fn»+«F8»(рис. -@fig:052)

![удаление строки](image/52.png){ #fig:052 width=70% }

Выделим фрагмент текста, нажав «fn»+«F3» для начала
выделения текста и для его окончания, и скопируем его на
новую строку, используя клавиши «fn»+«F5»(рис. -@fig:053)

![выделение и вставка строки](image/53.png){ #fig:053 width=70% }

Выделим фрагмент текста и перенесем его на новую строку с
помощью клавиш «fn»+«F6»(рис. -@fig:054)

![перенос на новую строку](image/54.png){ #fig:054 width=70% }

Сохраним файл, нажав «fn»+«F2»(рис. -@fig:055)

![сохраним файл](image/55.png){ #fig:055 width=70% }

Отменим последнее действие с помощью клавиш «ctrl»+«u» (рис. -@fig:056)

![отмена действия](image/56.png){ #fig:056 width=70% }

Перейдем в конец файла, нажав клавиши «ctrl»+«end» (переход
в конец файла) и «ctrl»+«x» (переход в конец следующего слова)(рис. -@fig:057)

![переход в конец файла](image/57.png){ #fig:057 width=70% }

(рис. -@fig:058)

![переход в конец следующего слова](image/58.png){ #fig:058 width=70% }

Перейдем в начало файла, нажав клавиши «ctrl»+«home»
(переход в начало файла) и «ctrl»+«z» (переход в начало
следующего слова)(рис. -@fig:059)

![переход в начало файла](image/59.png){ #fig:059 width=70% }

(рис. -@fig:060)

![переход в начало следующего слова](image/60.png){ #fig:060 width=70% }

Выполним сохранение файла (клавиши «fn»+«F2») и выход из
него (клавиши «fn»+«F10»)(рис. -@fig:061)

![сохранение файла](image/61.png){ #fig:061 width=70% }

5) Откроем файл с исходным текстом на некотором языке
программирования. Для этого воспользуемся командой «find / -name
*.java», чтобы посмотреть, какие файлы имеют расширение java (рис. -@fig:062)

![файлы на языках программирования](image/62.png){ #fig:062 width=70% }

Откроем файл в редакторе mc с помощью команды «mcedit путь_к_файлу»

6) Используя меню редактора «Команда» → «Включить/выключить
подсветку синтаксиса», выключим подсветку синтаксиса (рис. -@fig:063)

![подсветка синтаксиса](image/63.png){ #fig:063 width=70% }

3. Контрольные вопросы:
1) Панели могут дополнительно быть переведены в один из двух
режимов: «Информация» или «Дерево». В режиме «Информация» на
панель выводятся сведения о файле и текущей файловой системе,
расположенных на активной панели. В режиме «Дерево» на одной изпанелей выводится структура дерева каталогов.
2) Как с помощью команд shell, так и с помощью меню (комбинаций
клавиш) mc можно выполнить следующие операции с файлами:
копирование «F5» («cp имя_файла имя_каталога(в который копируем)») перемещение/переименование«F6»(«mv имя_файла имя_каталога(в который перемещаем)») 
создание каталога «F7» («mkdir имя_каталога») 
удаление «F8» («rm имя_файла»)
изменение прав доступа «ctrl+x» («chmod u+x имя_файла»)
3) Перейти в строку меню панелей mc можно с помощью функциональной клавиши «F9». В строке меню имеются пять меню:
«Левая панель», «Файл», «Команда», «Настройки» и «Правая
панель». Подпункт меню «Быстрый просмотр» позволяет выполнить быстрый
просмотр содержимого панели.Подпункт меню «Информация» позволяет посмотреть информацию о
файле или каталоге. В меню каждой (левой или правой) панели можно выбрать «Формат
списка»:
стандартный − выводит список файлов и каталогов с указанием
размера и времени правки;
ускоренный − позволяет задать число столбцов, на которые
разбивается панель при выводе списка имён файлов или
каталогов без дополнительной информации;
расширенный − помимо названия файла или каталога выводит
сведения о правах доступа, владельце, группе, размере,
времени правки;
определённый пользователем − позволяет вывести те сведения
о файле или каталоге, которые задаст сам пользователь.Подпункт меню «Порядок сортировки» позволяет задать критерии сортировки при выводе списка файлов и каталогов: без сортировки,
по имени, расширенный, время правки, время доступа, время
изменения атрибута, размер, узел.
4) Команды меню «Файл»:
Просмотр («F3») − позволяет посмотреть содержимое текущего
(или выделенного) файла без возможности редактирования.
Просмотр вывода команды («М» + «!») − функция запроса
команды с параметрами (аргумент к текущему выбранному
файлу).
Правка («F4») − открывает текущий (или выделенный) файл
для его редактирования.
Копирование («F5») − осуществляет копирование одного или
нескольких файлов или каталогов в указанное пользователем во
всплывающем окне место.
Права доступа («Ctrl-x» «c») − позволяет указать (изменить)
права доступа к одному или нескольким файлам или каталогам.
Жёсткая ссылка («Ctrl-x» «l») − позволяет создать жёсткую
ссылку к текущему (или выделенному) файлу.
Символическая ссылка («Ctrl-x» «s») − позволяет создать
символическую ссылку к текущему (или выделенному) файлу.
Владелец/группа («Ctrl-x» «o») − позволяет задать (изменить)
владельца и имя группы для одного или нескольких файлов или
каталогов.
Права (расширенные) − позволяет изменить права доступа и
владения для одного или нескольких файлов или каталогов.
Переименование («F6») − позволяет переименовать (или
переместить) один или несколько файлов или каталогов.
Создание каталога («F7») − позволяет создать каталог.
Удалить («F8») − позволяет удалить один или несколько файловили каталогов.
Выход («F10») − завершает работу mc.
5) Меню Команда
В меню Команда содержатся более общие команды для работы с mc.
Команды меню Команда:
 Дерево каталогов − отображает структуру каталогов системы.
 Поиск файла − выполняет поиск файлов по заданным
параметрам.
 Переставить панели − меняет местами левую и правую панели.
 Сравнить каталоги («Ctrl-x» «d») − сравнивает содержимое
двух каталогов.
 Размеры каталогов − отображает размер и время изменения
каталога (по умолчанию в mc размер каталога корректно не
отображается).
 История командной строки − выводит на экран список ранее
выполненных в оболочке команд.
 Каталоги быстрого доступа ( Ctrl-\») − при вызове выполняется
быстрая смена текущего каталога на один из заданного списка.
 Восстановление файлов − позволяет восстановить файлы на
файловых системах ext2 и ext3.
 Редактировать файл расширений − позволяет задать с помощью
определённого синтаксиса действия при запуске файлов с
определённым расширением (например, какое программного
обеспечение запускать для открытия или редактирования
файлов с расширением doc или docx).
 Редактировать файл меню − позволяет отредактировать
контекстное меню пользователя, вызываемое по клавише «F2».
 Редактировать файл расцветки имён − позволяет подобрать
оптимальную для пользователя расцветку имён файлов в
зависимости от их типа.6) Меню Настройки содержит ряд дополнительных опций по внешнему
виду и функциональности mc.
Меню Настройки содержит:
 Конфигурация − позволяет скорректировать настройки работы
с панелями.
 Внешний вид и Настройки панелей − определяет элементы
(строка меню, командная строка, подсказки и прочее),
отображаемые при вызове mc,а также геометрию
расположения панелей и цветовыделение.
 Биты символов − задаёт формат обработки информации
локальным терминалом.
 Подтверждение − позволяет установить или убрать вывод окна
с запросом подтверждения действий при операциях удаления и
перезаписи файлов, а также при выходе из программы.
 Распознание клавиш − диалоговое окно используется для
тестирования функциональных клавиш, клавиш управления
курсором и прочее.
 Виртуальные ФС − настройки виртуальной файловой системы:
тайм-аут, пароль и прочее.
7) Функциональные клавиши mc:
 F1 – вызов контекстно-зависимой подсказки
 F2 – вызов пользовательского меню с возможностью создания
и/или дополнения дополнительных функций
 F3 – просмотр содержимого файла, на который указывает подсветка в активной панели (без
возможности
редактирования)
F4 – вызов встроенного в mc редактора для изменения
содержания файла, на который указывает подсветка в активной
панели
 F5 – копирование одного или нескольких файлов, отмеченныхв первой (активной) панели, в каталог, отображаемый на второй
панели
 F6 – перенос одного или нескольких файлов, отмеченных в
первой (активной) панели, в каталог, отображаемый на второй
панели
 F7 – создание подкаталога в каталоге, отображаемом в активной
панели
 F8 – удаление одного или нескольких файлов (каталогов),
отмеченных в первой (активной) панели файлов
 F9 – вызов меню mc
 F10 – выход из mc
8) Встроенный в mc редактор вызывается с помощью функциональной
клавиши «F4». В нём удобно использовать различные комбинации
клавиш при редактировании содержимого (как правило текстового)
файла.
Клавиши для редактирования файла:
«Ctrl-y» − удалить строку
 «Ctrl-u» − отмена последней операции
 «ins» вставка/замена
 «F7» − поиск (можно использовать регулярные выражения)
 «↑-F7» − повтор последней операции поиска
 «F4» − замена
 «F3» − первое нажатие − начало выделения, второе − окончание
выделения
 «F5» − копировать выделенный фрагмент
 «F6» − переместить выделенный фрагмент
 «F8» − удалить выделенный фрагмент
 «F2» − записать изменения в файл
 «F10» − выйти из редактор
 9) Для редактирования меню пользователя, которое вызывается
клавишей «F2», необходимо перейти в пункт «Редактировать файл
меню» → «Команда» и изменить настройки файла.
10)
Часть команд «Меню пользователя», а также меню «Файл»
позволяют выполнять действия, определяемые пользователем, над
текущим файлом. Например, копирование каталога или файла,
переименование, перемещение, архивирование.

# Выводы

В ходе выполнения данной лабораторной работы я освоила основные возможности командной оболочки Midnight Commander и приобрела навыки практической работы по  просмотру каталогов и файлов;манипуляций с ними.