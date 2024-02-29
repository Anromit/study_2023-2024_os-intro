---
## Front matter
title: "Отчет по лабораторной работе 2"
subtitle: 
author: "Ромицына Анастасия"

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

# Цель работы
Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.



# Выполнение лабораторной работы

После установки git с помощью команды dnf install git, настраиваем unf-8 в вводе сообщений (рис. [-@fig:001]).

![Настройка unf-8](image/1.jpeg){#fig:001 width=70%}


Зададим имя начальной ветке (рис. [-@fig:002]).

![Имя ветки](image/2.jpeg){#fig:002 width=70%}


Настроим параметры autocfrlf(рис. [-@fig:003]).

![Параметры autocfrlf](image/3.jpeg){#fig:003 width=70%}


Настроим параметры safecrlf(рис. [-@fig:004]).

![Параметры safecrlf](image/4.jpeg){#fig:004 width=70%}


Создадим ключ ssh, скопируем его и введем в наш гит(рис. [-@fig:005]).

![Создание ssh](image/5.jpeg){#fig:005 width=70%}


Вводим наши данные и заходим в наш репозиторий(рис. [-@fig:006]).

![Подключение git](image/6.jpeg){#fig:006 width=70%}


Авторизовываемся в git(рис. [-@fig:007]).

![Авторизация](image/7.jpeg){#fig:007 width=70%}


Создадим необходимые каталоги(рис. [-@fig:008]).

![Создание каталога](image/10.jpeg){#fig:008 width=70%}


Создадим каталог курса и выгрузим его в наш гит (рис. [-@fig:009]).

![Выгрузка на git](image/8.jpeg){#fig:009 width=70%}




# Выводы

Мы смогли изучить идеологию и применение средств контроля версий.
У нас получилось освоить умения по работе с git.


# Список литературы{.unnumbered}

::: {#refs}
:::
