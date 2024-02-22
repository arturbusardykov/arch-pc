## Front matter
title: "Лабораторная работа №9. Понятие подпрограммы. Отладчик GDB."
subtitle: "НПМбв-02-21"
author: "Бусардыков Артур Валерьевич "

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



## Цель Работы:
Приобретение навыков написания программ с использованием подпрограмм. Знакомство
с методами отладки при помощи GDB и его основными возможностями.


## Выполнение работы

![image](https://github.com/arturbusardykov/arch-pc/assets/98996689/b006633c-3ef3-4cb7-ad41-06cb03c0f519)

Создал каталог и файл, выполнил и ввел X.

![image](https://github.com/arturbusardykov/arch-pc/assets/98996689/77d06d07-8f29-4887-a5ac-9730c3f72ee6)

Создал другой файл - lab09-2.asm и с помощью дополнительных параметров -g -l исполнил, и запустил с gdb.
Результат:
![image](https://github.com/arturbusardykov/arch-pc/assets/98996689/97ac3273-fc1d-4670-8298-a51f60bf8438)

Зашел в gdb, добавил точки остановки
![lab9-5](https://github.com/arturbusardykov/arch-pc/assets/98996689/05386f88-49f5-4c7a-90fd-caf741abbe31)



![lab9-6](https://github.com/arturbusardykov/arch-pc/assets/98996689/42876f33-c4f1-4b7d-a84b-d15dfe774956)
Провел работы по изучению команд:
Вывел на экран:

![lab9-7](https://github.com/arturbusardykov/arch-pc/assets/98996689/aec6ed1f-6b0f-4616-94a7-c58ec8e45ed6)

![lab9-8](https://github.com/arturbusardykov/arch-pc/assets/98996689/b3f7a39e-48eb-4963-8a06-f6a0d3fb1d3f)

## Вывод:
Приобрел навыки написания програм с использованием подпрограмм. 
Познакомился с методами отладки при помощи GDB и его основными возможностями 
