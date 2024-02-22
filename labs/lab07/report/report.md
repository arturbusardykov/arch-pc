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


## ЦЕЛЬ РАБОТЫ:
Изучение команд условного и безусловного переходов. Приобретение навыков написания
программ с использованием переходов. Знакомство с назначением и структурой файла
листинга

## План выполнения работы:
Cоздал каталог, переместился туда, создал файл lab7-1.asm
Ввел в него код из листинга

![lab7-1](https://github.com/arturbusardykov/arch-pc/assets/98996689/9b3381b8-0a69-431d-9742-68e4075d9b2c)

Запустил файл, получил сообщение на экран.

![lab7-2](https://github.com/arturbusardykov/arch-pc/assets/98996689/60063063-b198-451c-aa1f-34fd7f9db632)

Изменил файл с новым кодом из листинга.
Получил сообщение в обратном порядке.

## Далее
Создал файл lab7-2.asm с новым кодом. Дал файлу исполнение и запустил.
Сравнил пару символов и чисел.
![lab7-3](https://github.com/arturbusardykov/arch-pc/assets/98996689/853c3520-4abe-482b-bfd7-70fde68854b1)

## Вывод:

# Изучил команды условного и безусловного перехода. Приобрел навыки написания програм с использованием переходов. Познакомился с назначением и структурой файла листинга
