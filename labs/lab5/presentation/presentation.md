---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №5
subtitle: Модели хищник-жертва
author:
  - Лушин А.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Факультет Физико-математических и естественных наук
date: 18 февраля 2005

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Лушин Артём Андреевич
  * Бакалавр направления компьютерные и информационные науки
  * Кафедра теории вероятности и кибербезопасности
  * Российский университет дружбы народов
  * [lusin5745@gmail.com](mailto:lusin5745@gmail.com)

:::
::: {.column width="30%"}

![](/home/aalushin1/study_2024-2025_mathmod1/labs/lab3/presentation/image/me.jpg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

Реализовать на языке Julia и OpenModelica модель "хищник-жертва"

# Ход работы

## Модель хищник-жертва

Мы построили график изменения численности жертв и хищников на языке Julia. На графике чётко видны колебания. Затем построили график зависимости популяции хищников от жертв. Для сравнения построили аналогичные графики на языке OpenModelica. Графики с изменением популяции совпадают и колеблются. Графики с зависимости популяций также совпадают. Колебания объяснимы тем, что если падает количество жертв, то и количество хищников уменьшается. Если же количество жертв увеличивается, то и количество хищников также растёт. Чтобы посмотреть откуда идёт рост, построили график стационарного состояния на языке Julia. 

![](/home/aalushin1/study_2024-2025_mathmod1/labs/lab5/presentation/image/2.jpg)



# Результаты

## Вывод 

Я реализовал модель "хищник-жертва" на языке Julia и OpenModelica.

