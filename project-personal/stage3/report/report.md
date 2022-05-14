---
## Front matter
title: "Отчёт по третьей части индивидуального проекта"
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

Добавить к сайту достижения.

# Задание

* Добавить информацию о навыках
* Добавить информацию об опыте
* Добавить информацию о достижениях
* Сделать пост по прошедшей неделе
* Сделать пост по Markdown

# Выполнение лабораторной работы

 Добавляем информацию о навыках (рис.1)

![image](https://user-images.githubusercontent.com/104139992/168432603-ce5fa12c-7db0-4db5-97f6-ec839b4cbc78.png){рис.1}

Добавляем информацию об опыте (рис. 2)

![image](https://user-images.githubusercontent.com/104139992/168432735-a148a000-236d-4284-811a-aaeee7aed332.png){рис.2}

Добавляем информацию о достижениях (рис. 3)

![image](https://user-images.githubusercontent.com/104139992/168432812-71121760-cb4b-43b1-89d8-969826024782.png){рис.3}

Сделали пост по прошедшей неделе. (рис. 4 и 5)

![image](https://user-images.githubusercontent.com/104139992/168433365-957ed4c8-5269-44b8-8374-7a82977abeea.png){рис.4}

![image](https://user-images.githubusercontent.com/104139992/168433411-735e6df5-2520-43f1-9180-dd6ccf828279.png){рис.5}

Сделали публикацию по Markdown (рис. 6 и 7)

![image](https://user-images.githubusercontent.com/104139992/168433298-afc54f54-eb8c-46a0-8912-2a37d6a7d29d.png){рис. 6}


![image](https://user-images.githubusercontent.com/104139992/168433249-fed51b7f-81b9-4e5d-9a48-5403801985e8.png){рис. 7}

# Выводы

Внесли данные о себе и написали пост и эссе.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
