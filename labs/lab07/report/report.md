---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Дисциплина: Архитектура операционных систем"
author: "Люкшина Влада Алексеевна НПИбд-02-24"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.  


# Задание

Копирование, перемещение, переименование, создание, удаление файлов. Изменения прав доступа.  


# Выполнение лабораторной работы

Выполните все примеры, приведённые в первой части описания лабораторной работы.  

![примеры](11.png)  

перемещение файлов и создание директорий.  

![примеры](2.png)  

Изменения прав доступа.  

![примеры](3.png)  

1.Скопируйте файл /usr/include/sys/io.h в домашний каталог и назовите его equipment. 2.В домашнем каталоге создайте директорию ~/ski.plases. 3.Переместите файл equipment в каталог ~/ski.plases. 4.Переименуйте файл ~/ski.plases/equipment в ~/ski.plases/equiplist. 5. Создайте в домашнем каталоге файл abc1 и скопируйте его в каталог ~/ski.plases, назовите его equiplist2. 6. Создайте каталог с именем equipment в каталоге ~/ski.plases. 7. Переместите файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment. 8. Создайте и переместите каталог ~/newdir в каталог ~/ski.plases и назовите его plans.

![Копирование, перемещение, переименование, создание, удаление файлов](4.png)  

Определите опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет.  

![Изменения прав доступа.](5.png)  

Просмотрите содержимое файла /etc/password.  

![Просмотр](6.png)  

Скопируйте файл ~/feathers в файл ~/file.old. Переместите файл ~/file.old в каталог ~/play. Скопируйте каталог ~/play в каталог ~/fun. Переместите каталог ~/fun в каталог ~/play и назовите его games. Лишите владельца файла ~/feathers права на чтение. Что произойдёт, если вы попытаетесь просмотреть файл ~/feathers командой cat? Что произойдёт, если вы попытаетесь скопировать файл ~/feathers? Дайте владельцу файла ~/feathers право на чтение. Лишите владельца каталога ~/play права на выполнение. Перейдите в каталог ~/play. Дайте владельцу каталога ~/play право на выполнение.

![Изменения прав доступа файлов](7.png)  

# Выводы

В ходе лабораторной работы №7 мы научились работать с файлами: создавать, перемещать, переименовывать, копировать файлы. Менять права доступа.
