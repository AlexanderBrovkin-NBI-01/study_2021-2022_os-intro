---
## Front matter
lang: ru-RU
title: Текстовой редактор emacs
author: |
	  Бровкин Александр НБИбд-01-21\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: 4 мая, 2022, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

## Цель работы

Познакомиться с операционной системой Linux.Получить практические навыки работы с редактором emacs

## Выполнение лабораторной работы

# Создание нового файла с использованием emacs


1.Открыл emacs.


![рис.1](image/1.png)}

##

2.Создал файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f).

![рис.2](image/4.png)

##

3.Набрал текст:(

1 #!/bin/bash

2 HELL=Hello

3 function hello {

4 LOCAL HELLO=World

5 echo $HELLO

6 }

7 echo $HELLO

8 hello

##

![рис.3](image/6.png)


##

4. Сохранил файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s).

5. Проделал с текстом стандартные процедуры редактирования, каждое действие осуществлялось комбинацией клавиш.

5.1. Вырезал одной командой целую строку (С-k).

![рис.4](image/8.png)

##

5.2. Вставил эту строку в конец файла (C-y).


![рис.5](image/10.png)

##

5.3. Выделил область текста (C-space).

![рис.6](image/11.png)

##

5.4. Скопировал область в буфер обмена (M-w).

5.5. Вставил область в конец файла.

![рис.7](image/12.png)

##

5.6. Вновь выделил эту область и на этот раз вырезал её (C-w).
![рис.8](image/13.png)

##

5.7. Отменил последнее действие (C-/).

![рис.9](image/14.png)

##

6. Научился использовать команды по перемещению курсора.

6.1. Переместил курсор в начало строки (C-a).

![рис.10](image/17.png)

##

6.2. Переместил курсор в конец строки (C-e).

![рис.11](image/15.png)

##

Переместил курсор в начало буфера (M-<), а также переместил курсор в конец буфера (M->).

7. Управление буферами.

7.1. Вывел список активных буферов на экран (C-x C-b).

![рис.12](image/19.png)

##

7.2. Переместился во вновь открытое окно (C-x)  со списком открытых буферов и переключился на другой буфер.

![рис.13](image/19.png)

##

7.3. Закрыл это окно (C-x 0).

![рис.14](image/20.png)

 Вновь переключился между буферами, но без вывода их списка на экран (C-x b).

##

8. Управление окнами.

8.1. Поделил фрейм на 4 части: разделил фрейм на два окна по вертикали

(C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2)

![рис.15](image/22.png)

##

8.2. В каждом из четырёх созданных окон открыл новый буфер (файл) и ввел несколько строк текста.

![рис.16](image/24.png)

##

9. Режим поиска

9.1. Переключился в режим поиска (C-s) и нашел несколько слов, присутствующих в тексте.(

![рис.17](image/25.png)

##

9.2. Переключался между результатами поиска, нажимая C-s.

![рис.18](image/26.png)

##

9.3. Вышел из режима поиска, нажав C-g.

![рис.19](image/27.png)

##

9.4. Перешел в режим поиска и замены (M-%), ввел текст, который следует найти и заменить, нажал Enter , затем ввел текст для замены. После того как были подсвечены результаты поиска, нажал ! для подтверждения замены.

Cкрин со старого устройства

##

![рис.20](image/33.jpg)

##

9.5. Испробовал другой режим поиска, нажав M-s o. Он отличается от обычного режима тем, что при поиске указывает номера строк в которых найдено введённое слово и выделяет их цветом. В обычном режиме выделение цветом появляется, только когда нужно подтвердить замену.

##

![рис.21](image/28.png)

## Вывод

Познакомился с операционной системой Linux, получил практические навыки работы с редактором Emacs.


