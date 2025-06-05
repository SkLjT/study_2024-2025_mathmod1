---
## Front matter
title: "Отчёт по лабораторной работе №1" 
subtitle: "Знакомство с Git"
author: "Лушин Артём Андреевич"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: false
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомиться и настроить систему Git на персональной ОС.

# Выполнение лабораторной работы

1) У меня уже создан аккаунт гит, так как мы на нём работает с первого курса. Я взял шаблон репозитория для предмета "Математическое моделирование" и использовал на своём аккаунте, создав новый репозиторий.

![Создание репозитория](/home/aalushin1/study_2024-2025_mathmod1/labs/lab1/report/image/1.jpg){#fig:001 width=70%} 

2) С помощью команды я перенёс репозиторий на мою ОС Linux. Перенос был быстрый, так как на моей ОС уже есть аккаунт и он подключён к системе Git. 

![Перенос репозитория](/home/aalushin1/study_2024-2025_mathmod1/labs/lab1/report/image/2.jpg){#fig:002 width=70%} 

3) Я заполнил репозиторий шаблонами лабораторный работ, чтобы в дальнейшем было удобно работать. Также это было сделано для того, чтобы проверить работу всего репозитория. 

![Заполнение репозитория](/home/aalushin1/study_2024-2025_mathmod1/labs/lab1/report/image/3.jpg){#fig:003 width=70%}

4) С помощью серии команд, я отправил уже изменённый репозиторий с моей ОС на сайт Git. 

![Отправка репозитория](/home/aalushin1/study_2024-2025_mathmod1/labs/lab1/report/image/4.jpg){#fig:004 width=70%}

5) Проверил на сайте, что мои изменения пришли и вся система работает исправно. Всё работает!

![Проверка работоспособности](/home/aalushin1/study_2024-2025_mathmod1/labs/lab1/report/image/5.jpg){#fig:005 width=70%} 

# Вывод 

Я ознакомился и настроил систему Git на моей ОС. 
