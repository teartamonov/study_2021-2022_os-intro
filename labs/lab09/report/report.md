---
## Front matter
title: "Отчёт по лабораторной работе №9"
subtitle: "Текстовой редактор emacs"
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

* Познакомиться с операционной системой Linux. 
* Получить практические навыки работы с редактором Emacs.


# Задание 1

1. Открыть emacs
2. Создать файл lab07.sh
3. Набрать нужный текст
4. Сохранить файл
5. Проделать с текстом стандартные процедуры редактирования
6. Научиться использовать команды по перемещению курсора
7. Освоить управление буферами
8. Освоить управление окнами
9. Освоить режим поиска

# Теоретическое введение

* Буфер — объект, представляющий какой-либо текст.
* Фрейм соответствует окну в обычном понимании этого слова. Каждый фрейм содержит область вывода и одно или несколько окон Emacs.
* Окно — прямоугольная область фрейма, отображающая один из буферов.
* Область вывода — одна или несколько строк внизу фрейма, в которой Emacs выводит различные сообщения, а также запрашивает подтверждения и дополнительную информацию от пользователя.
* Минибуфер используется для ввода дополнительной информации и всегда отображается в области вывода.
* Точка вставки — место вставки (удаления) данных в буфере.

# Выполнение лабораторной работы

Создали файл и ввели в него текст в emacs, сохранили его. (рис. 1)

![image](https://user-images.githubusercontent.com/104139992/169267216-fb8f466e-f72c-4b02-92b8-cb127bc4b91d.png){рис. 1}

Проделали с текстом стандартные процедуры редактирования а также научились использовать команды по перемещению курсора. (рис. 2)

![image](https://user-images.githubusercontent.com/104139992/169267488-cdce7d02-34e2-4106-884e-dbf651289836.png){рис. 2}

Проделали различные махинации по взаимодействия с буферами. (рис. 3)

![image](https://user-images.githubusercontent.com/104139992/169267748-d870e4f9-acc5-4e3a-b167-8ef78626d0db.png){рис.3}

Освоили управление окнами. (рис. 4)

![image](https://user-images.githubusercontent.com/104139992/169267886-e9be1ee3-561e-448f-8e2c-d2af36baab76.png){рис. 4}

Освоили режим поиска. (рис. 5)

![image](https://user-images.githubusercontent.com/104139992/169268043-744165a5-e771-47cc-9f18-402a60603036.png){рис. 5}

# Контрольные вопросы

1. Emacs представляет собой мощный экранный редактор текста, написанный на языке высокого уровня Elisp.
2. Много горячих клавиш и древний интерфейс.
3. Буфер - какой-либо объект, являющийся текстом. Окно отображает один из буферов.
4. Да.
5. Fundamental.
6. * ctrl + c и shift + \
   * ctrl + c + shift + \
7. ctrl + x + (3 или 2)
8. В домашнем каталоге в файле .emacs.
9. Удаляет символ перед курсором. Да.
10. vi был удобнее. Обычному человеку не нужно столько функций, которые предоставляет emacs. 


# Выводы

Познакомились с операционной системой Linux. Получили практические навыки работы с редактором emacs.

# Список литературы

- Мой мозг
- Мой разум
- Моё сознание
- Лабораторная работа 9
- [Inspiration](https://youtu.be/7OYFay9Bel4)
