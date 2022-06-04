---
## Front matter
title: "Отчёт по лабораторной работе №14"
subtitle: "Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux"
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

* Приобрести простейшие навыки разработки,
* анализа,
* тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

# Задание

1. В домашнем каталоге создайте подкаталог ~/work/os/lab_prog
2. Создать в нём файлы: calculate.h, calculate.c, main.c
3. Выполнить компиляцию программы посредством gcc
4. Исправить синтаксические ошибки
5. Создать Makefile с содержанием
6. С помощью gdb выполнить отладку программы calcul 
7. С помощью утилиты splint проанализировать коды файлов calculate.c и main.c


# Теоретическое введение

`-c ` компиляция без компоновки — создаются объектные файлы file.o
`-o` file-name задать имя file-name создаваемому файлу
`-g` поместить в файл (объектный или исполняемый) отладочную информацию для отладчика gdb
`-MM` вывести зависимости от заголовочных файлов C и/или C++ программ в формате, подходящем для утилиты make; при этом объектные или исполняемые файлы не будет созданы
`-Wall` вывод на экран сообщений об ошибках, возникших во время компиляции

# Выполнение лабораторной работы

Создали файлы, переписали их содержимое, исправили ошибки. (рис. 1)

![image](https://user-images.githubusercontent.com/104139992/172015374-f40009e6-e684-4c87-ac10-e30603cd7db2.png){рис. 1}

Запустили gdb и запустили программу. (рис. 2)

![image](https://user-images.githubusercontent.com/104139992/172015446-709e5809-718b-486f-b347-f6c9133af0b2.png){рис. 2}

Установили точку останова. (рис. 3)

![image](https://user-images.githubusercontent.com/104139992/172015490-807a07e1-f323-4cbe-b8c4-cf42ede34359.png)

# Выводы

Приобрели простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
- Лабораторная работа 14
- [Inspiration](https://youtu.be/7OYFay9Bel4)
