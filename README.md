# АНАЛИЗ ДАННЫХ И ИСКУСТВЕННЫЙ ИНТЕЛЕКТ
Отчет по лабораторной работе #1 выполнил:
- Поляков Александр Дмитриевич
- РИ-230913 
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | ? |
| Задание 2 | * | ? |
| Задание 3 | * | ? |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:
- Скачать Anaconda и запустить Anaconda-Navigator.
- Запустить инструмент Jupyter Notebook и создать файл с именем HelloWorld.
- Открыть созданный файл с именем HelloWorld, написать в него команду print('Hello Word') с характерным содержанием и запустить выполнение, нажав Run.



![image]

## Задание 2
### Написать программу Hello World на C# с запуском на Unity.
Ход работы:
- Скачать Unity и авторизоваться.
- Скачать среду разработки для работы с C# (в моем случае Microsoft Visual Studio).
- Создать 3D проект.
- Добавить пустой GameObject.
- Написать скрипт компонента, который будет выводить в консоль "Hello World!".

```C#

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Helloworld : MonoBehaviour 
{
    void Start()
    {
        Debug.Log("Hello world!");
    }
}


```
- Повесить скрипт на объект и запустить проект.
  ![image]

## Выводы

Я узнал как скачивать Anaconda и Unity, а также узнал начальные этапы использования этих ПО.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
