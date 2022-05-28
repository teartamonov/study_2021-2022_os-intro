---
## Front matter
title: "Отчёт по пятой части индивидуального проекта"
author: "Артамонов Тимофей Евгеньевич"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Добавить к сайту всё остальное.

# Задание

* Редактировать пункт проектов
* Сделать пост по прошедшей неделе
* Сделать пост по подготовке отчётов

# Выполнение лабораторной работы

 Изменили пункт с проектами (рис.1)

![image](https://user-images.githubusercontent.com/104139992/170841234-4a30dce1-fa75-46f3-90e7-ed963f646dbb.png){рис. 1}

 Проверяем, всё ли работает (рис. 2)

![image](https://user-images.githubusercontent.com/104139992/170841231-cb415889-c287-4e8f-a533-5a7a807dfb91.png){рис. 2}

Сделали пост по прошедшей неделе. (рис. 3 и 4)

![image](https://user-images.githubusercontent.com/104139992/170841259-10cff191-07e6-4943-811a-55a4bf67a7c7.png){рис. 3}

![image](https://user-images.githubusercontent.com/104139992/170841268-8d357b9e-1dbf-491d-ab0a-200de5a2e01a.png){рис. 4}

Сделали публикацию (рис. 5 и 6)

![image](https://user-images.githubusercontent.com/104139992/170841263-0e9fc362-e820-4a9c-b607-4224625a01a7.png){рис. 5}

![image](https://user-images.githubusercontent.com/104139992/170841273-423700ee-75d0-4c12-8365-fd5e1a117442.png){рис. 6}

# Выводы

Добавили всё остальное и написали пост и эссе.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
- [Inspiration](https://youtu.be/7OYFay9Bel4)
