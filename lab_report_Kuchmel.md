﻿Кучмель Д.Д., гр. 110902

Лабораторная работа №5.

Высокопроизводительная обработка данных с Apache Spark

Целью данной лабораторной работы является освоение основных и расширенных функций Apache Spark для масштабируемой и эффективной обработки данных.

1. Установка, настройка и запуск Apache Spark

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.001.png)В ходе работы был установлен и настроен Apache Spark. Результат успешного запуска Apache Spark представлен на рисунке 1.

Рисунок 1 – Запуск Apache Spark

1. Понимание абстракции данных в Spark

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.002.png)Результат создания RDD с использованием Spark представлен на рисунке 2.

Рисунок 2 – Создание RDD

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.003.png)Выполнение преобразований RDD, с использованием увеличения в 2 раза каждого числа, представлено на рисунке 3.

Рисунок 3 – Преобразование RDD

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.004.png)Создание DataFrame из файла JSON и отображение схемы представлено на рисунке 4.

Рисунок 4 – Создание DataFrame

1. ` `Прием данных и управление схемами.

Загрузка данных из csv-файла в DataFrame и вывод схемы, с отображением столбцов DataFrame, представлена на рисунке 5.

![ref1]

Рисунок 5 – Загрузка данных из csv-файла

4\. Методы оптимизации производительности.

![ref2]Кэширование DataFrame для оптимизации повторяющихся запросов представлено на рисунке 6.

Рисунок 6 – Кэширование DataFrame

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.007.png)Просмотр физического плана операции с помощью метода explain() представлен на рисунке 7.

Рисунок 7 – Просмотр физического плана

5\. Обработка потока с помощью структурированного потока.

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.008.png)Настройка простого структурированного потокового запроса, считывающего данные из сокета, представлена на рисунке 8-10.

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.009.png)Рисунок 8 – Настройка структурированного потокового запроса

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.010.png)Рисунок 9 – Настройка структурированного потокового запроса 

Рисунок 10 – Результат настройки потокового запроса

6\. Расширенные операции с данными и подготовка к машинному обучению.

![](Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.011.png)Агрегация данных с помощью API DataFrame представлена на рисунке 11.

Рисунок 11 – Агрегация данных


[ref1]: Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.005.png
[ref2]: Aspose.Words.4cd9a232-0c0c-400e-ae16-4c9ab9f941bd.006.png