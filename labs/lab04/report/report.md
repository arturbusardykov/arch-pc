---
## Front matter
title: "Лабораторная работа No4. Создание и процесс обработки программ на языке ассемблера NASM"
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


##Цель работы:
Изучить процедуры компиляции и сборки программ, написанных на языке ассемблере NASM

##Порядок выполнения лабораторной работы:
![рис1](https://github.com/arturbusardykov/arch-pc/assets/98996689/17e24a72-631a-4bcd-931f-3f75e5bcd167)
Создал каталог, перешел в него, создал файл hello.asm.
Открыл его на редактирование и вставил текст из лабораторной.

##Далее
![рис2](https://github.com/arturbusardykov/arch-pc/assets/98996689/025bcc2d-598d-4d4a-89c1-f075f706f0c0)

Надо его транслировать. Написал команду для компиляции.
Выполнил команду с расширенным синтсаксисом и проверил наличие файла, затем выполнил команду с ключом -o.
Далее запустил файл с помощью ./hello.

##Задание для самостоятельной работы.

![рис2](https://github.com/arturbusardykov/arch-pc/assets/98996689/0e6707be-fd02-4f4b-aa54-b10d5e2b7781)

Скопировал эти файлы в папку с репозиторием, затем открыл файл lab4.asm для редактирования.
![рис3](https://github.com/arturbusardykov/arch-pc/assets/98996689/742a0bc1-294f-4a11-86e1-ae3ab3f49be6)

Повторил шаги трансляции и  компановки.
![рис5](https://github.com/arturbusardykov/arch-pc/assets/98996689/9a780f93-5e68-4627-8eaf-4aa369b9fe65)

Затем выполнил команду ./lab4.asm и вывелась Фамилия на экран.

![рис6](https://github.com/arturbusardykov/arch-pc/assets/98996689/fb760399-b128-42b3-9497-1863d041e78c)

Далее скопировал эти файлы в папку с лабораторными и запушил на гитхаб.









