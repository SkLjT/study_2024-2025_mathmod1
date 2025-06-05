---
## Front matter
title: "Отчёт по лабораторной работе №3" 
subtitle: "Математическое моделирование"
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

Реализовать модель боевых действий на языках OpenModelica и Julia. 

# Выполнение лабораторной работы

1) Я написал программу для построения графика модели боевых действий между регулярными войсками на языке Julia. В результате мы можем увидеть, что выигрывает армия У.

![Пример 1: код Julia](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/1.jpg){#fig:001 width=70%} 

![Пример 1: график Julia](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/2.jpg){#fig:002 width=70%} 

2) Написал такую же программу, но на языке OpenModelica. На этом языке также построил график и сравнил графики на двух языках. Графики идентичные. 

![Пример 1: код OpenModelica](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/3.jpg){#fig:003 width=70%}

![Пример 1: график OpenModelica](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/4.jpg){#fig:004 width=70%} 

3) Написал программу для построения графика модели боевых действий регулярных армий с участием партизанских отрядов на языке Julia. В данном случае побеждает армия Х, а численность армии У практически сразу уходит в ноль. 

![Пример 2: код Julia](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/5.jpg){#fig:005 width=70%} 

![Пример 2: график Julia](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/6.jpg){#fig:006 width=70%} 

4) Написал аналогичную программу на языке OpenModelica. Так же как и в случае с Julia, численность армии У практически сразу уходит в ноль. На данном графике это лучше видно, так как больше интервал. 

![Пример 2: код OpenModelica](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/7.jpg){#fig:007 width=70%} 

![Пример 2: графика OpenModelica](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/report/image/8.jpg){#fig:008 width=70%} 

# Вывод 

Я реализовал модель боевых действий на языке Julia и OpenModelica.


