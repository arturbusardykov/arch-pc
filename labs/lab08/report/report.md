---
## Front matter
title: "Лабораторная работа No7. Команды безусловного и условного переходов в Nasm. Программирование ветвлений."
subtitle: "НПМбв-02-21"
author: "Бусардыков Артур"

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

## Цель работы
Приобретение навыков написания программ с использованием циклов и обработкой
аргументов командной строки.

## Выполнение работы
![lab8-1](https://github.com/arturbusardykov/arch-pc/assets/98996689/3aeef6b7-4e27-446f-9aa6-3dff1e57f432)
Создал каталог и файл lab8-1.asm, ввел в него код из листинга. Запустил файл

![lab8-2](https://github.com/arturbusardykov/arch-pc/assets/98996689/e42bbac2-c875-4ef6-be1f-b498dfc23841)
Изменил файл и запустил

![lab8-3](https://github.com/arturbusardykov/arch-pc/assets/98996689/7a4e56b4-3613-45b6-b40d-5cababb1b80f)
Создал новый файл, ввел в него код из листинга
Запустил, увидел разницу.
![lab8-4](https://github.com/arturbusardykov/arch-pc/assets/98996689/fee1fb07-7b61-4549-b049-301cf894bfaa)
Опять изменил файл и вывел результат.



![lab8-5](https://github.com/arturbusardykov/arch-pc/assets/98996689/10684d3d-6a6c-491d-859d-b2d03bce133c)

Создал новый файл и запустил его с аргументами 
Получил результат с произведением аргументов
![lab8-6](https://github.com/arturbusardykov/arch-pc/assets/98996689/89a693ce-a34f-4b44-af2b-a38f25b31aa7)


# #Вывод:
Приобрел навыки написания програм с использованием циклов и обработкой аргументов командной строки



