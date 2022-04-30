---
## Front matter
title: "Отчёт по первой части индивидуального проекта"
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

Размещение на Github pages заготовки для персонального сайта.

# Задание

Установить необходимое программное обеспечение.
Скачать шаблон темы сайта.
Разместить его на хостинге git.
Установить параметр для URLs сайта.
Разместить заготовку сайта на Github pages.

# Выполнение 

Устанавливаем hugo, а также язык go. (рис.1)

![image](https://user-images.githubusercontent.com/104139992/166111489-715b68e9-8181-423f-949b-2aa8baac5ff4.png){рис.1}

Создаем новый репозиторий по шаблону. (рис.2)

![image](https://user-images.githubusercontent.com/104139992/166111598-4d3d6c3d-2fe7-4529-990b-d8c5e557efde.png){рис.2}

Клонируем его в гит и совершаем еще несколько действий. (рис.3)

![image](https://user-images.githubusercontent.com/104139992/166111669-bed25e7e-8f58-4a0f-9ab3-49e05c9ed9ab.png){рис.3}

Проверяем, что все работает. (рис.4)

![image](https://user-images.githubusercontent.com/104139992/166111809-539b4823-d56e-48bf-a878-f7dd391fbea4.png){рис.4}

Создаём пустой репозиторий. (рис.5)

![image](https://user-images.githubusercontent.com/104139992/166111929-f71088d0-bc57-4240-9b35-3bef9d68e0da.png){рис.5}

Клонируем его в гит. (рис.6)

![image](https://user-images.githubusercontent.com/104139992/166112006-f94dec1f-647f-4513-b868-b63f82567be5.png){рис.6}

Отключаем игнорирование папки public. (рис. 7, 8)

![image](https://user-images.githubusercontent.com/104139992/166112060-1bcafc05-2545-4732-b7c5-e786fcfa441f.png){рис.7}

Клонируем репозиторий в public. (рис.8)

![image](https://user-images.githubusercontent.com/104139992/166112139-6398b888-9164-48a6-9565-8327ab7e1feb.png){рис.8}

Выгружаем все на гитхаб. (рис. 9)
 
![image](https://user-images.githubusercontent.com/104139992/166112202-e5d9758f-0ec8-42f8-9010-63fad4368150.png){рис.9}

Проверяем что все работает. (рис.10)

![image](https://user-images.githubusercontent.com/104139992/166112265-1a72a598-85db-4d54-9a62-1696afa237b3.png){рис.10}

# Выводы

Создали свой сайт научника по шаблону

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
- https://youtu.be/OpsSv0RE3C4
