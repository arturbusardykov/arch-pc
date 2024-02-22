---
## Front matter
title: "Лабораторная работа №10. Работа с файлами средствами Nasm"
subtitle: "НПМбв-01-21"
author: "Ермаков Алексей"

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

## Цель работы:
Приобрести навыки написания программ для работы с разрешениями файлов

## Выполнение работы


Создал каталог, файл.
Исполнил файл и запустил
С помощью команды chmod 000 - отключил права на выполнение.
Также можно просто было написать 644 - чтение да, запись да, выполнение нет
![image](https://github.com/arturbusardykov/arch-pc/assets/98996689/85889d47-8393-4a4e-8479-72af2f2b6d38)

Чтобы добавить права на исполнение (1), можно написать 555, но смотря кому, если для всех - то это последняя цифра, для группы - вторая цифра, для себя - первая цифра.

Далее выдал права для файла readme-1.txt - для проверки.
![lab10-2](https://github.com/arturbusardykov/arch-pc/assets/98996689/c8ddfdf5-3cbf-4160-a937-3ce501df3e58)
![lab10-3](https://github.com/arturbusardykov/arch-pc/assets/98996689/9ea534e8-6f47-49e7-b832-d603329dfedd)
![lab10-3](https://github.com/arturbusardykov/arch-pc/assets/98996689/dce3530a-0333-4565-a74a-a6aba5a4ec63)

## Вывод 
Были получены навыки написания программ для работы с разрешениями файлов

