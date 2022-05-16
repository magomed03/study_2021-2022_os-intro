---
## Front matter
title: "4 этап реализации проекта"
subtitle: "Добавить на сайте ссылки на гитхаб и на какую-либо соц.сеть. Разместить посты"
author: "Мажитов Магомед Асхабович"

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

Добавить на сайте ссылки на гитхаб и на какую-либо соц.сеть. Разместить посты

# Задачи

Добавить к сайту ссылки на научные и библиометрические ресурсы.

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:

- github : https://github.com/.

Сделать пост по прошедшей неделе.

Добавить пост на тему по выбору:
- Оформление отчёта.
- Создание презентаций.
- Работа с библиографией.


# Выполнение лабораторной работы

**1.** Перешел в каталог /blog/content/authors/admin и открыл файл *index*. Затем я добавил ссылки на гитхаб и на вк. (рис. [-@fig:001])

![Добавление ссылок](image/1.png){ #fig:001 width=70% }

**2.** Запустил hugo server и посмотрел результат. (рис. [-@fig:002])

![Результат](image/2.png){ #fig:002 width=70% }

**3.** Создал необходимые посты.(рис. [-@fig:003])

![Создание постов](image/6.png){ #fig:003 width=70% }

**4.** Заполнил пост о прошедшей неделе.(рис. [-@fig:004])

![Пост о прошедшей неделе](image/4.png){ #fig:004 width=70% }

**5.** Заполнил пост об оформлении отчетов.(рис. [-@fig:005])

![Пост о оформлении отчетов](image/3.png){ #fig:005 width=70% }

**6.** Проверил добавились ли посты на сайте. (рис. [-@fig:006])

![Посты на сайте](image/5.png){ #fig:006 width=70% }

# Выводы

Мы добавили ссылки и создали посты.
