---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №7
subtitle: 
author:
  - Маслова А.П.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 10 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Маслова Анна Павловна
  * студентка, НПИбд-02-23
  * факультет физико-математических и естественных наук, направление прикладная информатиика
  * Российский университет дружбы народов
  * [1132236134@pfur.ru](mailto:1132236134@pfur.ru)
  
:::
::: {.column width="30%"}
:::
::::::::::::::


## Цели работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

# Выполнение лабораторной работы

## Первая часть лр

Выполните все примеры, приведённые в первой части описания лабораторной работы

![Первая часть лр](image/1.png){.column width="30%"}

## Файл equipment

Скопируйте файл `/usr/include/sys/io.h` в домашний каталог и назовите его `equipment`. Если файла `io.h` нет, то используйте любой другой файл в каталоге `/usr/include/sys/` вместо него.

![Файл equipment](image/2.png){.column width="30%"}

## Создание директории ~/ski.plases

В домашнем каталоге создайте директорию `~/ski.plases`

![Создание директории ~/ski.plases](image/3.png){.column width="30%"}

## Перемещение файла equiment

Переместите файл equipment в каталог `~/ski.plases`

![Перемещение файла equiment](image/4.png){.column width="30%"}

## Переименование файла equipment

Переименуйте файл `~/ski.plases/equipment` в `~/ski.plases/equiplist`

![Переименование файла equipment](image/5.png){.column width="30%"}

## Создание abc1

Создайте в домашнем каталоге файл `abc1` и скопируйте его в каталог `~/ski.plases`, назовите его `equiplist2`.

![Создание abc1](image/6.png){.column width="30%"}

## Создание каталога с именем equipment в каталоге ~/ski.plases.

Создайте каталог с именем `equipment` в каталоге `~/ski.plases`.

![Создание каталога с именем equipment в каталоге ~/ski.plases.](image/7.png){.column width="30%"}

## Перемещение файлов ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment

Переместите файлы `~/ski.plases/equiplist` и `equiplist2` в каталог `~/ski.plases/equipment`.

![Перемещение файлов ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment](image/8.png){.column width="30%"}

## Создайте и переместите каталог ~/newdir в каталог ~/ski.plases

Создайте и переместите каталог `~/newdir` в каталог `~/ski.plases` и назовите его `plans`.

![Создайте и переместите каталог ~/newdir в каталог ~/ski.plases](image/9.png){.column width="30%"}

## Определение прав доступа

Определите опции команды `chmod`, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет:
```
drwxr--r--  australia
drwx--x--x   play
-r-xr--r--   my_os
-rw-rw-r--   feathers
```
При необходимости создайте нужные файлы.

## Создание файлов

![Создание файлов](image/10.png){.column width="30%"}

## Определение прав доступа

![Определение прав доступа](image/11.png){.column width="30%"}

## Просмотр содержимого password

Просмотрите содержимое файла `/etc/password`.

![Просмотр содержимого password](image/12.png){.column width="30%"}

## Скопируем файл ~/feathers в файл ~/file.old

Скопируйте файл `~/feathers` в файл `~/file.old`.

![Скопируем файл ~/feathers в файл ~/file.old](image/13.png){.column width="30%"}

## Переместим файл ~/file.old в каталог ~/play

Переместите файл `~/file.old` в каталог `~/play`.

![Переместим файл ~/file.old в каталог ~/play](image/14.png){.column width="30%"}

## Скопируем каталог ~/play в каталог ~/fun

Скопируйте каталог `~/play` в каталог `~/fun`.

![Скопируем каталог ~/play в каталог ~/fun](image/15.png){.column width="30%"}

## Перемещение каталога ~/fun в каталог ~/play

Переместите каталог `~/fun` в каталог `~/play` и назовите его `games`.

![Перемещение каталога ~/fun в каталог ~/play](image/16.png){.column width="30%"}

## Лишение владельца файла ~/feathers права на чтение

Лишите владельца файла `~/feathers` права на чтение.

![Лишение владельца файла ~/feathers права на чтение](image/17.png){.column width="30%"}

## Команда cat и cp

Попытаемся просмотреть файл `~/feathers` командой `cat` и скопировать файл 

![Команда cat и cp](image/18.png){.column width="30%"}

## Дадим владельцу файла ~/feathers право на чтение

Дайте владельцу файла `~/feathers` право на чтение.

![Дадим владельцу файла ~/feathers право на чтение](image/19.png){.column width="30%"}

## Лишение владельца каталога ~/play права на выполнение

Лишите владельца каталога `~/play` права на выполнение

![Лишение владельца каталога ~/play права на выполнение](image/20.png){.column width="30%"}

## Переход в каталог ~/play

Перейдите в каталог `~/play`. Дайте владельцу каталога `~/play` право на выполнение.

![Переход в каталог ~/play](image/21.png){.column width="30%"}

## man mount

Прочитайте `man` по командам `mount`, `fsck`, `mkfs`, `kill`.

![man mount](image/22.png){.column width="30%"}

## man fsck

![man fsck](image/23.png){.column width="30%"}

## man mkfs

![man mkfs](image/24.png){.column width="30%"}

## man kill

![man kill](image/25.png){.column width="30%"}


# Выводы

Ознакомились с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрели практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.



