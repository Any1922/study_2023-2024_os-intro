---
## Front matter
title: "Отчёт по работе над персональным проектом"
subtitle: "Этап 2"
author: "Маслова Анна Павловна"

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


# Выполнение работы

Продолжаем разрабатывать свой сайт. 
Сейчас нам нужно прикрепить своё фото (рис. [-@fig:001]).

![Фото](image/1.png){#fig:001 width=70%}

Далее добавим информацию о себе: краткую информацию обо мне, об образовании и об интересах (рис. [-@fig:002]).

![Информация обо мне](image/2.png){#fig:002 width=70%}

Затем напишем первый пост: пост про мою прошедшую неделю. Заполним нужные поля: (рис. [-@fig:003])

![Пост про прошедшую неделю](image/3.png){#fig:003 width=70%}

Вторым постом будет статья о CI/CD (рис. [-@fig:004])

![Пост о CI/CD](image/4.png){#fig:004 width=70%}

Заполнив всё необходимое, мы можем теперь отправлять всё на GitHub. Сначала сделаем коммит из папки `blog`: (рис. [-@fig:005])

![Отправляем на Гитхаб из blog](image/5.png){#fig:005 width=70%}

Теперь делаем коммит из папки public: (рис. [-@fig:006])

![Отправляем на Гитхаб из public](image/6.png){#fig:006 width=70%}

Отправляемся на наш сайт: (рис. [-@fig:007])

![Страница с фото](image/7.png){#fig:007 width=70%}

Как мы видим, всё загрузилось.

Посмотрим посты: (рис. [-@fig:008])

![Посты](image/8.png){#fig:008 width=70%}

Второй этап подготовки проекта завершён!


