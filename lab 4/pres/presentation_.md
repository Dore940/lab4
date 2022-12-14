---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
author: |
	Доре Стевенсон Эдгар - студент группы НКНбд-01-19
date: 01.10.2022

## Formatting
toc: false
slide_level: 2
theme: focus
header-includes: 
 -	\usefonttheme{serif}
 -	\usepackage{fontspec}  
 -	\setmainfont{Times New Roman} 

aspectratio: 43
section-titles: true
---

# Работа с атрибутами файлов

## Цель выполнения лабораторной работы

- Получение практических навыков работы в консоли с расширенными атрибутами файлов


## Установка расширенного атрибута a

- От имени суперпользователя задаем расширенный атрибут `a` на файл `file1`

- Проверяем атрибуты файла от имени пользователя `guest`

![Добавление расширенного атрибута](image/1.jpg){ #fig:001 width=70% }

## Работа с файлом с расширенным атрибутом a

- Дозаписал текст в файл `file1`, прочитал файл

- Попробовал перезаписать информацию, а также снять атрибуты.

![Работа с файлом от имени guest](image/2.jpg){ #fig:002 width=70% }

## Работа с файлом без расширенного атрибута a

- Снял расширенный атрибут `a`

- Попробовал повторить предыдущие операции

![Повторение операций без расширенного атрибута](image/3.jpg){ #fig:003 width=70% }


## Работа с файлом с расширенным атрибутом i

- Установил расширенный атрибут `i` 

- Повторил операции: дозапись, перезапись, чтение, переименование

![Повторение операций с атрибутом i](image/4.jpg){ #fig:004 width=70% }


## Выводы

- В ходе выполнения лабораторной работы получили практические навыки работы в консоли с расширенными атрибутами файлов «а» и «i»