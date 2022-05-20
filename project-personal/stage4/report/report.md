---
## Front matter
title: "Отчёт по 4-ому этапу индвидуального проекта"
subtitle: "Ссылки на научные и библиометрические ресурсы"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору.

# Задание

1.Добавить к сайту ссылки на научные и библиометрические ресурсы.

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте(1):
eLibrary : https://elibrary.ru/;
Google Scholar : https://scholar.google.com/;
ORCID : https://orcid.org/;
Mendeley : https://www.mendeley.com/;
ResearchGate : https://www.researchgate.net/;
Academia.edu : https://www.academia.edu/;
arXiv : https://arxiv.org/;
github : https://github.com/.

2.Сделать пост по прошедшей неделе.

3.Добавить пост на тему по выбору:
Оформление отчёта.
Создание презентаций.
Работа с библиографией.


# Выполнение лабораторной работы

1.Я нашёл файл в каталоге блог , с помощью которого и произвёл редакцию шаблону и добавил ссылки и контакты .

Исправил контакты и адресс.

![2](image/2.png){Редакция контакта}

Далее убрал ненужные иконки и ссылки, и отредактировал нужные.

![1](image/1.png){ Редакция нужных ссылок }

![3](image/3.png){ Просмотр изменений 1 }

![4](image/4.png){ Просмотр изменений 2 }

2.Далее добавил пост по прошедшей неделе. С помощью редакции шаблона поста.

![5](image/5.png){ Редакция шаблона для поста 1 }

![6](image/6.png){  Редакция шаблона для поста 1 }

![7](image/7.png){ Проверка изменений }

3.Добавить пост на тему "Создание презнтаций"

![8](image/8.png){ Редакция шаблона поста для достижени нужной цели }

![10](image/10.png){ Проверка изменений }

# Выводы

Я добавил ссылки на ресурсы, добавил пост по прошедшей неделе, добавил по теме "Создание презентаций".

# Список литературы{.unnumbered}

::: {#refs}
:::
