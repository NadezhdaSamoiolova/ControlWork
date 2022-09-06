**СОДЕРЖАНИЕ ФАЙЛА README.MD**

1. [Условие задачи](#1-задача)
2. [Описание метода](#2-описание-метода)
3. [Описание основной программы](#3-описание-основной-программы)

### 1. **ЗАДАЧА** 

*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равно три символа*

### 2. **ОПИСАНИЕ МЕТОДА**

Необходимо взять метод с типом void, т.к. программа ничего не возвращает, а лишь записывает нужные значения. 

Программа берет на вход массив с типом данных string, состоящий из элементов типа string.

Открываем цикл for => заходим в условие. Если длина элемента массива меньше или равна трем, то этот элемент мы записываем в искомый массив. 

При этом важно, чтобы на выходе у вас получился красиво оформленный массив с открывающейся и закрывающейся квадратной скобкой и запятыми и пробелами между элементами. При этом после последнего элемента запятой не должно быть, а только скобка. Данное условие выполняется корректным употреблением команды Console.Write, а точнее корректным выбором содержания информации, подлежащей выводу (*как это показано в решении задачи*)

### 3. Описание основной программы

Массив, элементы которого мы будем анализировать, мы запрашиваем у пользователя. Мы просим его ввести элементы, разделяя их запятой. 

Мы записываем введенную пользователем информацию в переменную типа string. 

Далее мы разделяем полученную переменную на массив строк с разделителем в виде запятой и пустого символа. 

Затем мы приглашаем наш метод и в конце выводим результат.

