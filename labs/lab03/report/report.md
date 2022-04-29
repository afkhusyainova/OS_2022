---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Отчет по лабораторной работе"
author: "Хусяинова Адиля Фаритовна"

## Generic otions
lang: ru-RU



## Pdf output format
toc-depth: 2
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
  
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text

---

# Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.


# Задание
1) Сделать отчёт по предыдущей лабораторной работе в формате Markdown.
2) В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.).


# Выполнение лабораторной работы

1) Создаем учетную запись на GitHub и заполняем основные данные (рис.1)

![Создаем учетную запись на GitHub](image/1.png){ #fig:001 width=70% }

2)Настаиваем базовую конфигурацию git(рис.2)

![Настаиваем базовую конфигурацию git](image/2.png){ #fig:002 width=70% }

Необходимо задать имя и email владельца репозитория. Настраиваем веривикацию и подписание коммитов git.Задаем имя начальной ветки, параметр autocrlf и параметр safecrlf(рис.3)

![Необходимо задать имя и email владельца репозитория. Настраиваем веривикацию и подписание коммитов git.Задаем имя начальной ветки, параметр autocrlf и параметр safecrlf](image/3.png){ #fig:003 width=70% }

3)Теперь сгенирируем для ключа ssh и gpg и вставим в учетную запись github, чтобы привязать компьютер с github.

Создаем ключ ssh с помощью команды shh-keygen -t rsa -b 4096(рис.4)

![Создаем ключ ssh](image/4.png){ #fig:004 width=70% }

Копируем его в буфер обмена с помощью команды cat~/.ssh/id_rsa.pub | xclip -sel clip(рис.5)

![Копируем ключ ssh в буфер обмена](image/5.png){ #fig:005 width=70% }

Создаем ключ gpg с помощью команды gpg -full-generate-key и выбираем из предложенных вариантов, которые указаны в лабораторной работе(рис.6)

![Создаем ключ gpg](image/6.png){ #fig:006 width=70% }

Выводим список ключей, для того чтобы скопировать отпечаток приватного ключа(рис.7)

![Выводим список ключей](image/7.png){ #fig:007 width=70% }

Скопируем сгенерированный gpg ключ в буфер обмена(рис.8)

![Скопируем сгенерированный gpg ключ в буфер обмена](image/8.png){ #fig:008 width=70% }

Вставляем ключ ssh в аккаунт github(рис.9)

![Вставляем ключ ssh в аккаунт github](image/9.png){ #fig:009 width=70% }

Вставляем ключ gpg в аккаунт github(рис.10)

![Вставляем ключ gpg в аккаунт github](image/10.png){ #fig:0010 width=70% }

4) Воспользуемся введенным email и указываем git, применяем его при подписи коммитов(рис.11).

![Воспользуемся введенным email и указываем git](image/11.png){ #fig:0011 width=70% }

Создаем путь, где будут храниться материалы к лабораторным работам. Переходим в последнюю папку. Далее скачиваем шаблон репозитория в папку(рис.12)

![Скачиваем шаблон репозитория в папку](image/12.png){ #fig:0012 width=70% }

Создаем репозиторий на github.

Воспользуемся командой cd os-intro, создаем необходимые каталоги (make COURSE=os-intro)(рис.13)


![Воспользуемся командой cd os-intro, создаем необходимые каталоги](image/13.png){ #fig:0013 width=70% }


Перенесем в наш созданный репозиторий все файлы из папки os-intro, далее отправляем все файлы на сервер, чтобы они появились в репозитории github(рис.14,рис.15,рис.16)
 
![Переносим в репозиторий и отправляем все файлы на сервер](image/14.png){ #fig:0014 width=70% }
 
 
![Переносим в репозиторий и отправляем все файлы на сервер](image/15.png){ #fig:0015 width=70% }


![Переносим в репозиторий и отправляем все файлы на сервер](image/16.png){ #fig:0016 width=70% }


Чтобы убедиться в правильности выполнения действий открываем репозиторий в github(рис.17)


![Убеждаемся в правильности выполнения действий](image/17.png){ #fig:0017 width=70% }



# Выводы

Я научилась оформлять отчёты с помощью легковесного языка разметки Markdown.

::: {#refs}
:::
