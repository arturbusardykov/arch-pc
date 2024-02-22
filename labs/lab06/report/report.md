---
## Front matter
title: "Лабораторная работа №6. Арифметические операции в NASM."

author: "Бусардыков Артур Валерьевич"

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
Освоить арифметические операции языка ассемблера NASM

## Порядок выполнения лаб.работы:
![лаб_6-1](https://github.com/arturbusardykov/arch-pc/assets/98996689/ad4e2e64-c7cc-48ce-b3df-2e7a27cf7695)

![лаб_6-2](https://github.com/arturbusardykov/arch-pc/assets/98996689/4031b1d8-72b2-4767-b163-d27987bb98c7)
![лаб_6-3](https://github.com/arturbusardykov/arch-pc/assets/98996689/02e0f4f2-4a91-41d9-ba37-55dbccad2b50)

![лаб_6-4](https://github.com/arturbusardykov/arch-pc/assets/98996689/b3b73b67-d643-49d5-b0f4-c1fc99e1e96f)

![лаб_6-6PNG](https://github.com/arturbusardykov/arch-pc/assets/98996689/52385313-434d-4823-9411-e8227d68328e)

![лаб_6-7](https://github.com/arturbusardykov/arch-pc/assets/98996689/c4767911-c7d2-45ad-9dbf-f89790d225d2)



