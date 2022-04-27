---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Markdown"
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

– Изучить идеологию и применение средств контроля версий.
– Освоить умения по работе с git.

# Задание

* Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
* В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md


# Теоретическое введение

|   Символ     |   Действие	                                                                                                            |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| ` # `        | Заголовок                                                                                                                  |
| ` - `        | Неупорядоченный список                                                                                                     |
| ` * `        | Жирный текст                                                                                                               |
| ` ** `       | Курсив                                                                        	 					    |
| ` *** `      | Жирный курсив                                                                                   			    |
| ` ~n~0 `     | Нижний индекс n                                                                                   			    |
| ` ^n^ `      | Верхний индекс n                                                                                                           |

# Выполнение лабораторной работы

Берём предоставленный шаблон отчёта (рис.1)

![Шаблон](https://user-images.githubusercontent.com/104139992/165530257-8985b060-b735-4caf-8d0d-b1dc5a012981.png){рис. 1}

## Меняем всё необходимое
Пишем цель работы в соответсвии с руководством (рис. 2)

![Цель](https://user-images.githubusercontent.com/104139992/165530644-953d2061-2756-4dbd-85e7-fe176ab77b18.png){рис. 2}

Ставим задание в соответсвии с руководством (рис. 3)

![Задание](https://user-images.githubusercontent.com/104139992/165532106-87f770ee-2e25-4a46-a734-1479a05b78ae.png){рис. 3}

Пишем подходящее теоретическое введение (рис. 4)

![Теория](https://user-images.githubusercontent.com/104139992/165532404-23e41ac7-4929-4a10-8e86-004533de1cd9.png){рис. 4}

## Выполнение лабораторной работы

Переписываем всё из предыдущего отчёта и оформляем для Markdown(рис. 5)

![Отчёт](https://user-images.githubusercontent.com/104139992/165532939-4c8eb60b-9442-4e4b-8681-9663314ec505.png){рис. 5}

# Выводы

Научились пользоваться маркдауном и делать в нем отчёты.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
- https://esystem.rudn.ru/pluginfile.php/1383171/mod_resource/content/3/003-lab_markdown.pdf
