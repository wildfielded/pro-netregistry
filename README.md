<h3 align="center">:gb: Disclaimer</h3>

:warning: This project is intended for use primarily in a company with
Russian-speaking specialists. Therefore, all explanations, comments, and other
texts are provided exclusively in Russian.

----

# :ru: Реестр сетей и использования адресного пространства ЛВС #

![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54)

## Содержание ##

[1. Условия задания](#условия-задания)    
[2. Описание решения](#описание-решения)    
[3. Результат](#результат)    
[4. Инструкция по запуску проекта](#инструкция-по-запуску-проекта)    

## Условия задания ##

Есть две таблицы в MS Excel с данными по использованию IP-адресов из
делегированных диапазонов. Вечная процессная проблема&nbsp;&mdash; IP-адреса,
как всегда, выделяются и освобождаются в срочном порядке. Если тут же не
актуализировать информацию в таблицах, то потом придётся тратить гораздо больше
времени для воспоминаний, проверки и даже переинвентаризации. Сразу
актуализировать редко получается, поскольку процесс обложен
организационно-техническими решениями.Требуется облегчить процесс.

В таблице IP-адресов обязательны следующие поля:

1. IP адрес
2. Статус (свободен/временно/используется)
3. DNS-имя
4. Описание
5. Дата начала использования
6. Ответственный
7. Примечание

    IP адрес
    Статус (свободен/временно/используется)
    DNS-имя
    Описание
    Дата начала использования
    Ответственный
    Примечание

- Создать вэб приложения для записи информации и возможностью экспорта данных
в формат MS Excel по готовым шаблонам. Можно по одному или несколько листов в
файле.

- В качестве основы web-engine&nbsp;&mdash; использовать `Django`.

- В качестве СУБД&nbsp;&mdash; использовать `SQLite`. Для предполагаемого объёма
данных его достаточно.

- В качестве ORM-прокладки сделать выбор из вариантов: `django-orm`,
`SQLAlchemy`, `psycopg2` или что-то ещё.

[:arrow_up: Содержание](#содержание)

----

## Описание решения ##

[:arrow_up: Содержание](#содержание)

----

## Результат ##

[:arrow_up: Содержание](#содержание)

----

## Инструкция по запуску проекта ##

[:arrow_up: Содержание](#содержание)

----
