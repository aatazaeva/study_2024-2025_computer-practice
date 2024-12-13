---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Построение графиков"
author: "Тазаева Анастасия Анатольевна"

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

Основная цель работы — освоить синтаксис языка Julia для построения графиков.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 5.2.
2. Выполните задания для самостоятельной работы (раздел 5.4).

# Выполнение лабораторной работы

## Примеры из раздела 5.2



Примеры представлены на рис. [-@fig:001] - [-@fig:034]. Сохраненные файлы по заданиям располагаются в смежном каталоге lab5+samost/examples

![Установка пакетов для julia](image/1.png){#fig:001 width=70%}

![Примеры. Основные пакеты для работы с графиками в Julia. ч.1](image/2_1_1.png){#fig:002 width=70%}

![Примеры. Основные пакеты для работы с графиками в Julia. ч.2](image/2_1_2.png){#fig:003 width=70%}

![Примеры. Основные пакеты для работы с графиками в Julia. ч.3](image/2_1_3.png){#fig:004 width=70%}

![Примеры. Основные пакеты для работы с графиками в Julia. ч.4](image/2_1_4.png){#fig:005 width=70%}

![Примеры. Основные пакеты для работы с графиками в Julia. ч.5](image/2_1_5.png){#fig:006 width=70%}

![Примеры. Опции при построении графика. ч.1](image/2_2_1.png){#fig:007 width=70%}

![Примеры. Опции при построении графика. ч.2](image/2_2_2.png){#fig:008 width=70%}

![Примеры. Опции при построении графика. ч.3](image/2_2_3.png){#fig:009 width=70%}

![Примеры. Простой точечный график.](image/2_3_1.png){#fig:010 width=70%}

![Примеры. Точечный график с кодированием значения размером точки.](image/2_3_2.png){#fig:011 width=70%}

![Примеры. 3-мерный точечный график с кодированием значения размером точки. ](image/2_3_3.png){#fig:012 width=70%}

![Примеры. Аппроксимация данных.](image/2_4.png){#fig:013 width=70%}

![Примеры. Две оси ординат.](image/2_5.png){#fig:014 width=70%}

![Примеры. Полярные координаты.](image/2_6.png){#fig:015 width=70%}

![Примеры. Параметрический график кривой на плоскости и в пространстве](image/2_7.png){#fig:016 width=70%}

![Примеры. График поверхности. ч.1](image/2_8_1.png){#fig:017 width=70%}

![Примеры. График поверхности. ч.2](image/2_8_2.png){#fig:018 width=70%}

![Примеры. Линии уровня. ч.1](image/2_9_1.png){#fig:019 width=70%}

![Примеры. Линии уровня. ч.2](image/2_9_2.png){#fig:020 width=70%}

![Примеры. Векторные поля](image/2_10_1.png){#fig:021 width=70%}

![Примеры. Gif-анимация](image/2_11_1.png){#fig:022 width=70%}

![Примеры. Гипоциклоида](image/2_11_2.png){#fig:023 width=70%}

![Примеры. Errorbars. ч.1](image/2_12_1.png){#fig:024 width=70%}

![Примеры. Errorbars. ч.2](image/2_12_2.png){#fig:025 width=70%}

![Примеры. Errorbars. ч.3](image/2_12_3.png){#fig:026 width=70%}

![Примеры. Errorbars. ч.4](image/2_12_4.png){#fig:027 width=70%}

![Примеры. Использование пакета Distributions. ч.1](image/2_13_1.png){#fig:028 width=70%}

![Примеры. Использование пакета Distributions. ч.2](image/2_13_2.png){#fig:029 width=70%}

![Примеры. Использование пакета Distributions. ч.3](image/2_13_3.png){#fig:030 width=70%}

![Примеры. Подграфики. ч.1](image/2_14_1.png){#fig:031 width=70%}

![Примеры. Подграфики. ч.2](image/2_14_2.png){#fig:032 width=70%}

![Примеры. Подграфики. ч.3](image/2_14_3.png){#fig:033 width=70%}

![Примеры. Подграфики. ч.4](image/2_14_4.png){#fig:034 width=70%}

## Самостоятельная работа

Примеры представлены на рис. [-@fig:035] - [-@fig:045]. Сохраненные файлы по заданиям располагаются в смежном каталоге lab5+samost/samost.

![Задание 1](image/s1.png){#fig:035 width=70%}

![Задание 2](image/s2.png){#fig:036 width=70%}

![Задание 3](image/s3.png){#fig:037 width=70%}

![Задание 4](image/s4.png){#fig:038 width=70%}

![Задание 5](image/s5.png){#fig:039 width=70%}

![Задание 6](image/s6.png){#fig:040 width=70%}

![Задание 7](image/s7.png){#fig:041 width=70%}

![Задание 8](image/s8.png){#fig:042 width=70%}

![Задание 9](image/s9.png){#fig:043 width=70%}

![Задание 10](image/s10.png){#fig:044 width=70%}

![Задание 11](image/s11.png){#fig:045 width=70%}


# Выводы

В ходе лабораторной работы мною был освоен синтаксис языка Julia для построения графиков.

