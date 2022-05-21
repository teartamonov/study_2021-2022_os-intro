---
## Front matter
title: "Отчёт по четвертой части индивидуального проекта"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Задание

* Разместить ссылки на сайте
* Сделать пост по прошедшей неделе
* Сделать пост по подготовке отчётов

# Выполнение лабораторной работы

 Добавляем ссылки (рис.1)

![image](https://user-images.githubusercontent.com/104139992/169654645-85fad7b1-dd93-4c0a-9090-d3c0c27654af.png){рис. 1}

 Проверяем, всё ли работает (рис. 2)

![image](https://user-images.githubusercontent.com/104139992/169654690-2b3fb7dd-d48c-4214-a021-5e57c5a7f0e3.png){рис. 2}

Сделали пост по прошедшей неделе. (рис. 3 и 4)

![image](https://user-images.githubusercontent.com/104139992/169654728-c0d30794-2170-46f2-81f7-163fc3d24599.png){рис. 3}

![image](https://user-images.githubusercontent.com/104139992/169654741-65b6f194-8ca9-4bda-8bda-eec58a10e9e7.png){рис. 4}

Сделали публикацию по Markdown (рис. 5 и 6)

![image](https://user-images.githubusercontent.com/104139992/169654747-ce64de4b-34c8-4894-b9fc-fd6f5b23ff0e.png){рис. 5}

![image](https://user-images.githubusercontent.com/104139992/169654755-01f498f6-a24d-46b6-97dc-9ed2a98e0aab.png){рис. 6}

# Выводы

Добавили контактные ссылки и написали пост и эссе.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
- [Inspiration](https://youtu.be/7OYFay9Bel4)
