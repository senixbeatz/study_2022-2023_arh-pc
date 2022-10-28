---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: Архитектура компьютера
author: "Павлов Арсений Валерьевич"

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
Изучить идеологию и применение средств контроля
версий, а также приобрести практические навыкипо работе с системой
git.
# Задание
1. Создайте отчет по выполнению лабораторной работы в соответствующем
каталоге рабочего пространства (labs>lab03>report).
2. Скопируйте отчеты по выполнению предыдущих лабораторных работ в
соответствующие каталоги созданного рабочего пространства.
3. Загрузите файлы на github.
# Выполнение лабораторной работы
1. Сначала сделаем предварительную конфигурацию git. Откроем
терминал и введём следующие команды, указав имя и email
владельца репозитория:
• Настроим utf-8 в выводе сообщений git:
• Зададим имя начальной ветки (будем называть её master):
• Параметр autocrlf:
• Параметр safecrlf:
![Открытие каталога курса](image/3.png)

![Открытие каталога курса](image/4.png)

![Открытие каталога курса](image/5.png)

![Открытие каталога курса](image/6.png)

![Открытие каталога курса](image/7.png)

2. Создание SSH ключа 2.4.3
![Открытие каталога курса](image/8.png)

![Открытие каталога курса](image/9.png)

![Открытие каталога курса](image/10.png)
Вставляем ключ в появившееся на сайте поле и указываем для
ключа имя (Title)
3. Создание рабочего пространства и репозитория курса
на основе шаблона
![Открытие каталога курса](image/11.png)

![Открытие каталога курса](image/12.png)
4. Создание репозитория курса на основе шаблона 2.4.5
![Открытие каталога курса](image/13.png)

![Открытие каталога курса](image/14.png)

![Открытие каталога курса](image/15.png)

5. Откройте терминал и перейдите в каталог курса
![Открытие каталога курса](image/16.png) 

Клонируеем созданный репозиторий:
![Открытие каталога курса](image/17.png) 

![Открытие каталога курса](image/18.png)
6. Настройка каталога курса 2.4.6

![Открытие каталога курса](image/19.png)
 
![Открытие каталога курса](image/20.png)
 
![Открытие каталога курса](image/21.png)

![Открытие каталога курса](image/22.png

![Открытие каталога курса](image/23.png)

# Выводы
Мы изучили идеолгию и применение средств контроля
версий. Приобрели практические навыки по работе с системой
git .
# Список литературы

