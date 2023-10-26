# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Нигматзянов Никита Сергеевич
- НМТ-210509
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | # | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

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
Познакомиться с программными средствами для создания системы машинного обучения и ее интеграции в Unity.
## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления: or, and, nand, xor.
## ОR
![image](https://user-images.githubusercontent.com/113620568/202668438-a72865f8-d7e4-4be3-8e1a-2666fb5f2de9.png)
![image](https://user-images.githubusercontent.com/113620568/202668653-4f57311c-e8ba-4842-bd0a-52b5ce737d56.png)
Скорость обучения перцептрона на Unity высока, за 4 эпохи он научиося выполнять без ошибок операцию OR
## AND
У перцептрона ушло 8 эпох для того, чтобы научиться работать с операцией and
![image](https://user-images.githubusercontent.com/113620568/202669935-a2bdee60-4ba8-4937-b202-6a08abd933f5.png)
## NAND
Перцептрон обучился за 8 эпох, но на 2 эпохе значение TOTAL ERROR достигает 3, затем на 3 эпохе 1 и после 0. После чего программа работает стабильно
![image](https://user-images.githubusercontent.com/113620568/202670966-a69e855b-bbf7-4693-a8f5-5e282f54fa4f.png)
## XOR
Данную операцию перцептрон не в состоянии решить, т.к. перцептрон работает только с линейно разделимыми объектами, он не способен решить данную логическую задачу, потому что для её решения потребуется разделить данные двумя линиями. 
![image](https://user-images.githubusercontent.com/113620568/202674646-d5df4393-e452-4f2e-ad40-e1c0b4169104.png)


## Задание 2
### Построить графики зависимости количества эпох от ошибки обучения. Указать от чего зависит необходимое количество эпох обучения.
## ОR
![image](https://user-images.githubusercontent.com/113620568/202672175-a22aa880-1f06-4508-914d-79786d756bf5.png
## AND
![image](https://user-images.githubusercontent.com/113620568/202672311-cc2c239c-b634-43d5-931a-b5d56d5a0517.png)
## NAND
![image](https://user-images.githubusercontent.com/113620568/202672450-1edb00b9-d740-4592-a35c-c61202675a59.png)
## XOR
![image](https://user-images.githubusercontent.com/113620568/202672586-a64ab33e-cf62-4f90-aa4b-fd5496026c4b.png)
## Количество эпох обучения зависит от:
## -Количества вводных данных
## -Шага обучения
## -Увеличения ошибки обобщения
## Выводы



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
