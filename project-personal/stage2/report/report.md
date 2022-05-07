---
## Front matter
title: "Отчёт по второй части индивидуального проекта"
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

Добавить к сайту данные о себе.

# Задание

* Разместить фотографию владельца сайта.
* Разместить краткое описание владельца сайта.
* Добавить информацию об интересах.
* Добавить информацию от образовании.
* Сделать пост по прошедшей неделе.
* Добавить пост на тему по выбору.

# Выполнение лабораторной работы

## Добавляем данные о себе

Изменили фото профиля, поменяли биографию а также интересы и образование. (рис.1)

![image](https://user-images.githubusercontent.com/104139992/167258994-1d38940d-eaaf-44eb-bfab-223e30025577.png){рис.1}

## Пост по прошедшей неделе

Изменяем уже имеющийся пост на свой. (рис. 2 и 3)

![image](https://user-images.githubusercontent.com/104139992/167259135-f7aea61c-c33d-49d2-b20b-2085f2419d01.png){рис.2}

![image](https://user-images.githubusercontent.com/104139992/167259156-b4862956-f1b9-48fe-808a-c94d2dda8504.png){рис.3}

## Эссе

Изменили уже имеющуюся публикацию и написали эссе. (рис. 4 и 5)

![image](https://user-images.githubusercontent.com/104139992/167259207-171e0bf1-e103-4d1c-9bee-052836a9a010.png){рис.4}

![image](https://user-images.githubusercontent.com/104139992/167259256-83b0927e-e404-4046-9076-f39fa803dfd7.png){рис.5}


# Выводы

Внесли данные о себе и написали пост и эссе.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
