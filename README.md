ИТОГОВАЯ КОНТРОЛЬНАЯ РАБОТА (1)

Задача : 
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. 
При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

Алгоритм решения задачи:
1. Создаются два массива из одинакового количества эолементов - array 1, array 2.
2. Запускается цикл по длине массива
3. Внутри цикла проверяется условие: количество символов в строке меньше либо равно 3 ( <=3 ). 
4. Если "да", то элемент первого массива заносится в count второго массива. 
5. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. Также она сразу возвращается к циклу, если "нет".
6. Print 


Блок-схема по задаче (размещение на гугл-диске):
https://app.diagrams.net/#G16SmX7KdUgQjjTtjvFRFEBG2utDubrw-j


Программный код:
Program.cs
