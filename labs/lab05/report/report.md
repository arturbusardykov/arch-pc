## Front matter
title: "Лабораторная работа №5. Основы работы с Midnight Commander (mc). Структура программы на языке ассемблера NASM. Системные вызовы в ОС GNU Linux"
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


## Цель работы
Приобрести навыки работы в Midnight Commander. Использовать инструкции языка ассемблера mov и int.

## Порядок выполнения работы 
 ![лаб51](https://github.com/arturbusardykov/arch-pc/assets/98996689/f8d3067e-bd87-4767-8db1-adb715ce467b)
![лаб52](https://github.com/arturbusardykov/arch-pc/assets/98996689/3c44683a-39f2-4109-b9e6-a718e2a2be6b)

Открыл mc, создал подпапку lab05 и файл lab5-1.asm.
Затем зашел в каталог и вставил из лабораторной программу выводу сообщений на экран в lab5-1.asm.

Транслировал и скомпонавал, проверил на выполнение и ввел ФИО.
![лаб53](https://github.com/arturbusardykov/arch-pc/assets/98996689/e2fbf4b7-cf95-40ce-a19d-419c33840806)


Создал копию и переместил её в конец файла lab5-1.asm, затем создал копию с именем lab5-2.asm
![лаб54](https://github.com/arturbusardykov/arch-pc/assets/98996689/192a9237-d48e-4b35-ad6e-6a27a7aade09)

Проверил файл на выполнение
![лаб55](https://github.com/arturbusardykov/arch-pc/assets/98996689/5c9023d6-94ec-47f8-a2b2-bd2a3c08036a)

## Вывод:
Приобрел навыки работы в Midnight Commander, использовал инструкции языка ASEMBLER mov и int

