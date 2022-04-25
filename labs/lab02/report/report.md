---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Управление версиями"
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

– Создать базовую конфигурацию для работы с git.
– Создать ключ SSH.
– Создать ключ PGP.
– Настроить подписи git.
– Зарегистрироваться на Github.
– Создать локальный каталог для выполнения заданий по предмету

# Теоретическое введение

Git - Система контроля версий (Version Control System, VCS) применяется при работе нескольких человек над одним проектом.
Ветвление - сохранение версий проекта для возможного последующего использования.
Хранилище - место, где хранятся все версии проекта.
commit - изменение в проекте.
Рабочая версия - версия проекта, над которой в данный момент ведется работа.
GitHub - веб-сервис, основанный на системе контроля версий Git.

# Выполнение лабораторной работы

## Настройка github
Регистрируем учётную запись github и заполняем основные данные. (рис.1)

![Профиль в GitHub](https://user-images.githubusercontent.com/104139992/165083905-8bbb4d0d-af23-4b30-aaf4-f008e72955eb.png){рис.1}

## Установка программного обеспечения

Устанавливаем git-flow в Fedora. (рис.2)

![Терминал](https://user-images.githubusercontent.com/104139992/165087838-e8086f2b-5ef4-4eb3-acfc-7a4efabf7225.png){рис.2}

Устанавливаем gh. (рис.3)

![Терминал](https://user-images.githubusercontent.com/104139992/165088051-b8673702-4c8d-4898-bb06-652596b81bfc.png){рис.3}

## Настройка git

Зададим имя и email владельца репозитория, то есть нас. (рис.4)

![Терминал](https://user-images.githubusercontent.com/104139992/165088290-2c10799f-c33a-4164-a764-c038e22f1b52.png){рис.4}

Зададим имя начальной ветки и параметры. (рис.5)

![Терминал](https://user-images.githubusercontent.com/104139992/165088774-67146e7d-3e62-4142-b585-c55472c0bd3c.png){рис.5}

## Создание ключей ssh и добавление их в GitHub


# Выводы![image]

Создаем ed25519 ключ и точно так же rsa. (рис.6)

![Создание ssh ключей](https://user-images.githubusercontent.com/104139992/165088991-d55c9610-3c50-46e3-b996-a3f19449fbd4.png){рис.6}

Копируем ключи в буфер и по очереди добавляем их в гитхаб. (рис. 7, 8)

![Копирование ssh ключей](https://user-images.githubusercontent.com/104139992/165089151-cbe69a39-2a96-44d4-b213-4f81dd481503.png){рис.7}
![Вставка](https://user-images.githubusercontent.com/104139992/165089360-6aa354fa-8775-4a81-9cd9-4a2dd4439c0e.png){рис.8}


Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
