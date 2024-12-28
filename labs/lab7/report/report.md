---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Введение в работу с данными"
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

Основной целью работы является освоение специализированных пакетов для обработки данных.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 7.2.
2. Выполните задания для самостоятельной работы (раздел 7.4).

# Выполнение лабораторной работы

## Примеры из раздела 6.2

Примеры представлены на рис. [-@fig:001] - [-@fig:021]. 

![Считывание данных. Часть 1](image/1.png){#fig:001 width=70%}

![Считывание данных. Часть 2](image/2.png){#fig:002 width=70%}

![Считывание данных. Часть 3](image/3.png){#fig:003 width=70%}

![Словари](image/4.png){#fig:004 width=70%}

![DataFrames](image/5.png){#fig:005 width=70%}

![RDatasets](image/6.png){#fig:006 width=70%}

![Работа с переменными отсутствующего типа (Missing Values). Часть 1](image/7.png){#fig:007 width=70%}

![Работа с переменными отсутствующего типа (Missing Values). Часть 2](image/8.png){#fig:008 width=70%}

![Кластеризация данных. Метод k-средних. Часть 1](image/9.png){#fig:009 width=70%}

![Кластеризация данных. Метод k-средних. Часть 2](image/10.png){#fig:010 width=70%}

![Кластеризация данных. Метод k-средних. Часть 3](image/11.png){#fig:011 width=70%}

![Кластеризация данных. Метод k-средних. Часть 4](image/12.png){#fig:012 width=70%}

![Кластеризация данных. Метод k-средних. Часть 5](image/13.png){#fig:013 width=70%}

![Кластеризация данных. Метод k-средних. Часть 6](image/14.png){#fig:014 width=70%}

![Кластеризация данных. Метод k ближайших соседей. Часть 1](image/15.png){#fig:015 width=70%}

![Кластеризация данных. Метод k ближайших соседей. Часть 2](image/16.png){#fig:016 width=70%}

![Кластеризация данных. Метод главных компонент. Часть 1](image/17.png){#fig:017 width=70%}

![Кластеризация данных. Метод главных компонент. Часть 2](image/18.png){#fig:018 width=70%}

![Обработка данных. Линейная регрессия. Часть 1](image/19.png){#fig:019 width=70%}

![Обработка данных. Линейная регрессия. Часть 2](image/20.png){#fig:020 width=70%}

![Обработка данных. Линейная регрессия. Часть 3](image/21.png){#fig:021 width=70%}

## Самостоятельная работа

Примеры представлены на рис. [-@fig:022] - [-@fig:026]. 

![Кластеризация. Часть 1](image/22.png){#fig:022 width=70%}

![Кластеризация. Часть 2](image/23.png){#fig:023 width=70%}

![Кластеризация. Часть 3](image/24.png){#fig:024 width=70%}

![Регрессия. Часть 1](image/25.png){#fig:025 width=70%}

![Регрессия. Часть 2](image/26.png){#fig:026 width=70%}


# Выводы

В ходе лабораторной работы мною были освоены специализированные пакеты для обработки данных.

