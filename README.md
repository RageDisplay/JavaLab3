# Динамический массив

# Задача

**Задача:** реализовать контейнер `MyVector` — динамический массив для хранения произвольного типа данных.

# **Указания по выполнению**

Лабораторная работа состоит из **двух файлов**:

- *MyVector.java* — описание класса vector, прототипы методов, реализация методов
- *TestVector.java* — тестирование и проверка возможностей класса

Класс `MyVector` должен быть шаблонным.

Класс `MyVector` должен содержать следующие **поля**:

- ссылку на массив
- текущее число элементов
- максимальное число элементов

Класс `MyVector` должен содержать следующие **методы**:

- конструктор
- конструктор копирования
- добавление элемента в конец
- удаление последнего элемента
- удаление элемента по индексу
- вставка элемента по индексу
- изменение размера массива
- очистка массива (удаление всех элементов)
- получение текущего и максимального размера контейнера

Пользователь должен иметь возможность задать начальное число элементов в массиве с помощью конструктора.

Память под массив должна выделяться с запасом. Можно придерживаться простейшей стратегии: макс. число элементов = 2*(число элементов) + 10.

Если число элементов за счет добавления новых превышает максимальное, необходимо заново выделить память, скопировать существующие элементы.

При невозможности удаления элемента, доступа к элементу и т. п. должны генерироваться исключения.