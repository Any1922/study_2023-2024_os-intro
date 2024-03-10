---
## Front matter
title: "Очёт по лабораторной работе №5"
subtitle: "дисциплина: Операционные системы"
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

# Цель работы

Ознакомиться с настройкой `dotfiles` и научиться использовать менеджер паролей `pass`. Ознакомиться с `chezmoi`. Научиться углубленной работе с `git`.

# Выполнение лабораторной работы

Для начала установим менеджер паролей `pass` и `gopass` (рис. [-@fig:001], [-@fig:002]).

![Установка pass](image/1.jpg){#fig:001 width=70%}

![Установка gopass](image/2.jpg){#fig:002 width=70%}

Просмотрим список ключей, инициализируем хранилище и синхронизируем с `git` (рис. [-@fig:003]).

![Инициализация](image/3.jpg){#fig:003 width=70%}

Зададим адрес репозитория на хостинге (рис. [-@fig:004]).

![Синхронизация репозитория на хостинге](image/4.jpg){#fig:004 width=70%}

Закоммитим изменения (рис. [-@fig:005]).

![Коммит изменений](image/5.jpg){#fig:005 width=70%}

Проверили статус синхронизации.
Настроим интерфейс с браузером (рис. [-@fig:006], [-@fig:007]).

![Настройка интерфейса с браузером](image/6.jpg){#fig:006 width=70%}

![Настройка интерфейса с браузером](image/7.jpg){#fig:007 width=70%}

Добавим новый пароль, отобразим и изменим его (рис. [-@fig:008]).

![Добавление пароля](image/8.jpg){#fig:008 width=70%}

Далее для управления файлами конфигурации установим дополнительное программное обеспечение (рис. [-@fig:009]).

![Установка дополнительного ПО](image/9.jpg){#fig:009 width=70%}

Установим шрифты (рис. [-@fig:010], [-@fig:011]).

![Установка шрифтов](image/10.jpg){#fig:010 width=70%}

![Установка шрифтов](image/11.jpg){#fig:011 width=70%}

Установим бинарный файл (рис. [-@fig:012]).

![Установка бинарного файла](image/12.jpg){#fig:012 width=70%}

Создадим репозиторий и подключим его к своей системе (рис. [-@fig:013]).

![Подключение репозитория](image/13.jpg){#fig:013 width=70%}

Запустим `chezmoi diff` и проверим, какие изменения внесёт `chezmooi` в домашний каталог (рис. [-@fig:014]).

![Запуск chezmoi diff](image/14.jpg){#fig:014 width=70%}

Изменения нас устраивают, поэтому следующей командой будет `chezmoi apply -v`.

Для проверки работы `chezmoi` на разных машинах запустим виртуальную машину, созданную при прохождении курса "Архитектура компьютера", и инициализируем на неё `chezmoi` с нашим репозиторием `dotfiles` (рис. [-@fig:015]).

![Другая виртуальная машина](image/15.jpg){#fig:015 width=70%}

Проверили внесённые изменения, и они нас устраивают.
Установим наши `dotfiles` на эту машину (рис. [-@fig:016]).
 
![Установка ditfiles а новую машину](image/16.jpg){#fig:016 width=70%}

Извлечём изменения из репозитория (рис. [-@fig:017]).

![Извлечение изменений](image/17.jpg){#fig:017 width=70%}

Настроим автоматическую отправку изменений в репозиторий (рис. [-@fig:018]).

![Автоматическая фиксация и отправка изменений](image/18.jpg){#fig:018 width=70%}

# Выводы

Ознакомились с настройкой `dotfiles` и научились использовать менеджер паролей `pass`. Ознакомились с `chezmoi`. Научились углубленной работе с `git`.

# Список литературы{.unnumbered}

1. Dash, P. Getting Started with Oracle VM VirtualBox / P. Dash. – Packt Publishing Ltd, 2013. – 86 сс.
2. Colvin, H. VirtualBox: An Ultimate Guide Book on Virtualization with VirtualBox. VirtualBox / H. Colvin. – CreateSpace Independent Publishing Platform, 2015. – 70 сс.
3. Vugt, S. van. Red Hat RHCSA/RHCE 7 cert guide : Red Hat Enterprise Linux 7 (EX200 and EX300) : Certification Guide. Red Hat RHCSA/RHCE 7 cert guide / S. van Vugt. – Pearson IT Certification, 2016. – 1008 сс.
4. Робачевский, А. Операционная система UNIX / А. Робачевский, С. Немнюгин, О. Стесик. – 2-е изд. – Санкт-Петербург : БХВ-Петербург, 2010. – 656 сс.
5. Немет, Э. Unix и Linux: руководство системного администратора. Unix и Linux / Э. Немет, Г. Снайдер, Т.Р. Хейн, Б. Уэйли. – 4-е изд. – Вильямс, 2014. – 1312 сс.
6. Колисниченко, Д.Н. Самоучитель системного администратора Linux : Системный администратор / Д.Н. Колисниченко. – Санкт-Петербург : БХВ-Петербург, 2011. – 544 сс.
7. Robbins, A. Bash Pocket Reference / A. Robbins. – O’Reilly Media, 2016. – 156 сс.
