---
## Front matter
title: "Индивидуальный проект - 2 этап"
subtitle: "Работа с сайтом"
author: "Бровкин Александр НБИбд-01-21"

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

# Цель работы: 

Научиться оформлять сайт, менять информацию о себе и создавать несколько постов.

# Ход работы:

Для начала я должен добавить на свой сайт личную фотографию, делаю это через файлы в папке blog. (рис. [-@fig:001])

![Личная фотография на сайте](image/1.png){ #fig:001 width=70% } 

Далее мы должны добавить информацию о себе, а именно свое имя, вуз и биографию.(рис. [-@fig:002])(рис. [-@fig:003])

![bio](image/7.png){ #fig:002 width=70% } 

![bio](image/8.png){ #fig:003 width=70% } 


Далее я должен добавить пост по прошедшей неделе(рис. [-@fig:004])

![post last week](image/10.png){ #fig:004 width=70% } 

Сам сайт со всеми изменениями я покажу в конце


Также пишу еще один пост на тему по выбору, я выбрал тему-Управление версиями Гит(рис. [-@fig:005])(рис. [-@fig:006])

![Еще один пост](image/15.png){ #fig:005 width=70% } 


![Пост](image/16.png){ #fig:006 width=70% } 


А теперь сам сайт:(рис. [-@fig:007])(рис. [-@fig:008])(рис. [-@fig:009])(рис. [-@fig:010])(рис. [-@fig:011])(рис. [-@fig:012])

![Заглавная страничка сайта](image/17.png){ #fig:007 width=70% } 

![Посты](image/18.png){ #fig:008 width=70% } 

![Пост первый про прошлую неделю](image/13.png){ #fig:009 width=70% } 

![Пост первый про прошлую неделю](image/14.png){ #fig:010 width=70% } 

![Второй пост про управление версиями гит](image/19.png){ #fig:011 width=70% } 

![Второй пост про управление версиями гит](image/20.png){ #fig:012 width=70% } 


# Вывод:

Я научился оформлять личный сайт, а также создавать посты.

















