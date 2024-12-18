---
## Front matter
title: "Лабораторная работа №6"
subtitle: "Решение моделей в непрерывном и дискретном времени"
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

Основной целью работы является освоение специализированных пакетов для решения задач в непрерывном и дискретном времени.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 6.2.
2. Выполните задания для самостоятельной работы (раздел 6.4).

# Выполнение лабораторной работы

## Примеры из раздела 6.2

Примеры представлены на рис. [-@fig:001] - [-@fig:008]. 

![Модель экпоненциального роста. Часть 1](image/1.png){#fig:001 width=70%}

![Модель экпоненциального роста. Часть 2](image/2.png){#fig:002 width=70%}

![Модель экпоненциального роста. Часть 3](image/3.png){#fig:003 width=70%}

![Система Лоренца. Часть 1](image/4.png){#fig:004 width=70%}

![Система Лоренца. Часть 2](image/5.png){#fig:005 width=70%}

![Система Лоренца. Часть 3](image/6.png){#fig:006 width=70%}

![Модель Лотки-Вольтерры. Часть 1](image/7.png){#fig:007 width=70%}

![Модель Лотки-Вольтерры. Часть 2](image/8.png){#fig:008 width=70%}


## Самостоятельная работа

Примеры представлены на рис. [-@fig:009] - [-@fig:021]. 

![Задание 1](image/s1.png){#fig:009 width=70%}

![Задание 1. Продолжение](image/s1_2.png){#fig:010 width=70%}

![Задание 2](image/s2.png){#fig:011 width=70%}

![Задание 2. Продолжение](image/s2_2.png){#fig:012 width=70%}

![Задание 3](image/s3.png){#fig:013 width=70%}

![Задание 3. Продолжение](image/s3_2.png){#fig:014 width=70%}

![Задание 4](image/s4.png){#fig:015 width=70%}

![Задание 4. Продолжение](image/s4_2.png){#fig:016 width=70%}

![Задание 5](image/s5.png){#fig:017 width=70%}

![Задание 6](image/s6.png){#fig:018 width=70%}

![Задание 7](image/s7.png){#fig:019 width=70%}

![Задание 8](image/s8.png){#fig:020 width=70%}

![Задание 8. Продолжение](image/s8_2.png){#fig:021 width=70%}


# Выводы

В ходе лабораторной работы мною были освоены специализированные пакеты для решения задач в непрерывном и дискретном времени.

