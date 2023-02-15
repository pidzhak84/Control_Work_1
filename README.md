# **Итоговая проверочная работа**

## **ЗАДАЧА:**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна трем символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## **Порядок выполнения:**

1. Создание репозитория.

2. Добавление файла gitignore.

3. Составление блок-схема алгоритма.

4. Добавление файла README для оформления текстового описания решения задачи.

5. Написание программы, решающей поставленную задачу.

6. Оформление файла README, в котором описаны:
* порядок выполнения поставленной задачи;
* этапы написанной программы для решения задачи;
* метод, описывающий алгоритма.


## **Этапы решения задачи:**
1. Ввод количества элементов массива
2. Ввод первоначального массива - ввод каждого элемента массива с клавиатуры.
3. Вывод итогового массива.


## **Метод, описывающий алгоритм:**

1. Получение массива, вводимого с клавиатуры.

2. Cравнивнение длины каждого элемента массива со  значением, определенным в задании - *3 символа*.

3. Если длина элемента массива <= 3, то элемент выводится в итоговом массиве, если нет, то установленный цикл продолжается.

4. После сравненияе всех элементов имеющегося массива выводятся:
* первоначальный массив;
* итоговый массив.