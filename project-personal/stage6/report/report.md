---
## Front matter
title: "Отчет по 6-ому этапу индивидуального проекта"
subtitle: "Перевод на второй язык всех элементов"
author: "Михаил Евгеньевич Морозов"

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

Размещение двуязычного сайта на Github.

Сделать поддержку английского и русского языков.
Разместить элементы сайта на обоих языках.
Разместить контент на обоих языках.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору (на двух языках).

# Задание

Размещение двуязычного сайта на Github.

Сделать поддержку английского и русского языков.
Разместить элементы сайта на обоих языках.
Разместить контент на обоих языках.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору (на двух языках).



# Выполнение лабораторной работы

Я изменил конфиг сайта для того чтобы подключить поддержку двух языков

![1](image/1.png){ Изменил конфиг }

Посмотрел изменения на локальном хосте.

![2](image/2.png){ Проверил на локальном хосте }

Добавил пост на русскому языке.

![3](image/3.png){ Написал пост  }

Перевел его и посмотрел изменения.

![4](image/4.png){ Проверил на локальном хосте }

Добавил сообщение по теме "Северное сияние"

![5](image/5.png){ Написал сообщение/доклад}

Проверил измения на английском языке.

![6](image/6.png){ Проверил изменения }
# Выводы

Я сделал поддержку сайта на английском и русском языке. Я разместил элементы сайта, а также контент на обоих языках, сделал прси пр прошедшей неделе, и добавил пост на тему "Северное сияние".

# Список литературы{.unnumbered}

::: {#refs}
:::
