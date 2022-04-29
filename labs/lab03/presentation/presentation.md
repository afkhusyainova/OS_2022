---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
author: Хусяинова Адиля Фаритовна
date: NEC--2022,28 апреля

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Отчет по лабораторной работе №3

# Работа с Markdown

Записываем и оформляем цель и задания лабораторной работы (рис.1)

Лабораторная работа №3 строится на предыдущей лабораторной работе, поэтому мы копируем основные моменты

![Работа с Markdown](1.png){ #fig:001 width=70% }

# Ход работы

Расписываем алгоритм работы с лабораторной работы №2

Необходимо указать полную ссылку для каждого изображения(Пример офрмления ссылки показан на скриншоте)(рис.2)

![Необходимо указать полную ссылку для каждого изображения](2.png){ #fig:002 width=70% }


# Выполнение лабораторной работы

Алгоритм выполнения лабораторной работы №2 в Markdown(рис.4)
 
![Алгоритм выполнения лабораторной работы №2 в Markdown](3.png){ #fig:003 width=70% }

![Алгоритм выполнения лабораторной работы №2 в Markdown](4.png){ #fig:004 width=70% }

# Создание отчета в трех форматах

С помощью команды pandoc report.md -o report.docx создадим отчет в формате dock.Воспользовавшись командой pandoc -o report.pdf -f markdown --pdf-engine=xelatex report.md создадим отчет в формате pdf       (рис.5) (рис.[-@fig:007]) (рис.[-@fig:006])
создадим отчет в формате pdf

![С помощью команды pandoc report.md -o report.docx создадим отчет в формате dock.Воспользовавшись командой pandoc -o report.pdf -f markdown --pdf-engine=xelatex report.md создадим отчет в формате pdf](5.png){ #fig:005 width=70% }

![Воспользовавшись командой pandoc -o report.pdf -f markdown --pdf-engine=xelatex report.md создадим отчет в формате pdf] (7.png) { #fig:007 width=70% }

![С помощью команды pandoc report.md -o report.docx создадим отчет в формате dock.] (6.png) { #fig:006 width=70% }


# Выводы

Приобрела навыки работы в Markdown

Научилась создавать pdf и dock файлы

Сделала отчет по предыдущей лабораторной работе №2


