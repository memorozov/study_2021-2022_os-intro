---
## Front matter
title: "Отчёт по 5-му этупу индивидуального проекта"
subtitle: "5-й этап"
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
1.Добавить с сайту все остальные элементы.

Сделать записи для персональных проектов.

2.Сделать пост по прошедшей неделе.

3.Добавить пост на тему по выбору.
Языки научного программирования.


# Задание

1.Добавить с сайту все остальные элементы.

Сделать записи для персональных проектов.

2.Сделать пост по прошедшей неделе.

3.Добавить пост на тему по выбору.
Языки научного программирования.

# Выполнение лабораторной работы

Я перешёл к шаблону с соответсвенным название project personal и начал его редакцию , так как я ещё не сделал свой персональный проект , я решил что заполню все графы позже как только он будет готов, но для того чтобы было видно что я проделал работу , я изменил название и содержание этого поста.

![1](image/1.png){ Редакция шаблона }

![2](image/2.png){ Тест изменений на сайте }

После этого я перешёл к созданию поста по предыдущей неделе и создал соответсвующий пост по средствам редакции шаблона прошлого недельного поста.

![3](image/3.png){ Редакция шаблона поста}

![4](image/4.png){ Тест изменений на сайте }

Далее перешёл к последнему этапу этого этапа индивидуального проекта а именносоздал пост-доклад по теме : Научные языки программирования 

![5](image/5.png){ Создание поста-доклада на тему }

![6](image/6.png){ Тест изменений на сайте }

# Выводы

Я сделал записи для персонального проекта , сделал пост по прошедшей неделе и добавил пост по теме: Языки научного программирования

# Список литературы{.unnumbered}

::: {#refs}
:::
