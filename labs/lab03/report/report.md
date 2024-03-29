---
## Front matter
title: "Лабораторная работа No3. Язык разметки Markdown"
subtitle: ""
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

::: {#refs}
:::
 ## Цель работы
Освоить процедуры оформления отчетов с помощью языка разметки Markdown

## Задание
В соответствующем каталоге сделайте отчёт по лабораторной работе No 2 в формате Markdown. В качестве отчёта необходимо предоставить отчёты в 3 форматах: pdf, docx и md.
Загрузите файлы на github.
Выполнение лабораторной работы
Спомощью команды cd мы перешли в директорию /work/study/2023-2024/"Архитектура компьютера"/arch-pc/labs/lab03/report, а затем спомощью команды make создали файлы report.docx report.md report.pdf 
![лаб3-1](https://github.com/arturbusardykov/arch-pc/assets/98996689/0a32c36d-82ca-4575-9f90-dc662313efbe)
![лаб3-2](https://github.com/arturbusardykov/arch-pc/assets/98996689/a26312de-da23-4a9e-abfa-350d07099d24)




И затем загрузил на github



## Выводы
В этой работе мы научились работать с языком Markdown используя средства командной строки.



