---
# Front matter
lang: ru-RU
title: "Лабораторная работа №2"
subtitle: "Практикум по научному письму"
author: "Нонога Джинтоба"

## Generic otions

toc-title: "Содержание"


## Pdf output format
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

## Цель работы
Познакомиться с языком LaTeX и освоить основные команды.

## Задание
Реализовать основные команды.

## Лабораторные Работы
Создадим свой первый документ.
В данной программе мы подключаем соответствующий формат, открываем командой begin и пишем текст. Завершаем командой end.
Далее представлен результат работы программы.

![  1](1.png)

В данной программе мы добавили знак процента, посмотрели, что он преобразует всю следующую строку в комментарий. Так же посмотрели как работает перенос на другую строку (пустая строка) и посмотрели на работу символа ~. Попробовали экранирование и написали в кавычки как часть текста, а не команду. Посмотрели на разные классы документов.

![  2](2.png)



## Выводы
Познакомился с языком LaTeX и освоить основные команды.