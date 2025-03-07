---
## Front matter
title: "Лабораторная работа №3"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown. С помощью Markdown будут оформляться все отчеты по лабораторным работам.  


# Задание

Сделайте отчёт по предыдущей лабораторной работе в формате Markdown, после чего преобразовать в pdf и docx.  


# Выполнение лабораторной работы

Открываем папку с шаблоном отчета по лабораторной работе №2 в формате md. Изменяем заголовки и ФИО.  

![Работа с заголовками](image/1.png)  

Прописываем цель работы и вывод, детально описываем весь ход работы, прикрепляем скриншоты.  

![Работа с файлом](image/2.png)  

Сохраняем файл и открываем терминал. Переходим в наш каталог report и используем команду make. У нас создаются файлы report.pdf и report.docx.  

![Создаем новые файлы](image/3.png)  

Проверяем наличие файлов и их корректность.  

![Проверка](image/4.png)  


# Выводы

В ходе лабораторной работы №3 мы научились создавать отчеты в формате md, которые впоследствие можно преобразовать в файлы типов docx и pdf с помощью команды make.
