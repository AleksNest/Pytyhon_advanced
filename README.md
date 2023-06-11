# СЕМИНАР 1 Основы Python
1. Задание 1
    - Установили Python и IDE для работы
2. Задание 2
      - Работаем в командной строке (терминале ОС)
      - Создайте каталог для проекта first_project и разверните
      - виртуальное окружение Python в папке venv внутри каталога
      - Создайте третий каталог проекта project_new и разверните
      виртуальное окружение Python в папке venv_new внутри каталога
      - Для каждого проекта последовательно активируйте
      и деактивируйте виртуальное окружение
3. Задание 3
      - Активируем виртуальное окружение первого из трёх созданных проектов
   и устанавливаем в него модуль requests используя pip
      - Проверяем установку выводом списка модулей в консоль
      - Сохраняем список в файл, проверяем результат и выходим из окружения
      - Активируем виртуальное окружение второго из трёх созданных проектов
      и устанавливаем в него модуль flask используя pip
      - Проверяем установку выводом списка модулей в консоль
      Сохраняем список в файл и выходим из окружения
      - Активируем третье виртуальное окружение
      - Устанавливаем в него модули из первого и второго проекта используя
      ранее сохранённые в файлы списки модулей
      - Проверяем установку выводом списка модулей в консоль
4. Задание 4 
      - Работа в консоли в режиме интерпретатора Python.
      - Решите квадратное уравнение 5x2-10x-400=0 последовательно
   сохраняя переменные a, b, c, d, x1 и x2.
     - *Попробуйте решить уравнения с другими значениями a, b, c
5. Задание 5 
     - Работа в консоли в режиме интерпретатора Python.
     - Посчитайте сумму чётных элементов от 1 до n исключая кратные e.
     - Используйте while и if.
     - Попробуйте разные значения e и n.
6. [Задание 6](Seminar_1/Task_1_6.py)  
     - Напишите программу, которая запрашивает год и проверяет его на високосность.
     - Распишите все возможные проверки в цепочке elif
     - Откажитесь от магических чисел
     - Обязательно учтите год ввода Григорианского календаря
     - В коде должны быть один input и один print
7. [Задание 7](Seminar_1/Task_1_7.py)  
     - Пользователь вводит число от 1 до 999. Используя операции с числами
сообщите что введено: цифра, двузначное число или трёхзначное число.
     - Для цифры верните её квадрат, например 5 - 25
     - Для двузначного числа произведение цифр, например 30 - 0
     - Для трёхзначного числа его зеркальное отображение, например 520 - 25
     - Если число не из диапазона, запросите новое число
     - Откажитесь от магических чисел
     - В коде должны быть один input и один print
8. [Задание 8](Seminar_1/Task_1_8.py)  
     - Нарисовать в консоли ёлку спросив
     - у пользователя количество рядов.
     - Пример результата:
     - Сколько рядов у ёлки? 5
9. [Задание 9](Seminar_1/Task_1_9.py)  
     - Выведите в консоль таблицу умножения от 2х2 до 9х10 как на школьной тетрадке
10. [ДОМАШНЯЯ РАБОТА](Homework/Seminar_1/Task_1_10.py)
     - Треугольник существует только тогда, когда сумма любых двух его сторон больше третьей. Дано a, b, c —
стороны предполагаемого треугольника. Требуется сравнить длину каждого отрезка-стороны с суммой
двух других. Если хотя бы в одном случае отрезок окажется больше суммы двух других, то треугольника
с такими сторонами не существует. Отдельно сообщить является ли треугольник разносторонним,
равнобедренным или равносторонним.
     -  Напишите код, который запрашивает число и сообщает является ли оно простым или составным.
Используйте правило для проверки: «Число является простым, если делится нацело только на единицу
и на себя». Сделайте ограничение на ввод отрицательных чисел и чисел больше 100 тысяч.
     - Программа загадывает число от 0 до 1000. Необходимо угадать число за 10 попыток. Программа
должна подсказывать «больше» или «меньше» после каждой попытки. Для генерации случайного
числа используйте код:
     - from random import randint
num = randint(LOWER_LIMIT, UPPER_LIMIT) 

# СЕМИНАР 2 Простые типы данных
1. [Задание 1](Seminar_2/Task_2_1.py)
    - Создайте несколько переменных разных типов.
    - Проверьте к какому типу относятся созданные переменные
2. [Задание 2](Seminar_2/Task_2_2.py)
    - Создайте в переменной data список значений разных типов перечислив их через
запятую внутри квадратных скобок. Для каждого элемента в цикле выведите:
    - ✔ порядковый номер начиная с единицы
    - ✔ значение
    - ✔ адрес в памяти
    - ✔ размер в памяти
    - ✔ хэш объекта
    - ✔ результат проверки на целое число только если он положительный
    - ✔ результат проверки на строку только если он положительный
    - Добавьте в список повторяющиеся элементы и сравните на результаты.
3. [Задание 3](Seminar_2/Task_2_3.py)
    - Напишите программу, которая получает целое число и возвращает
его двоичное, восьмеричное строковое представление.
    - ✔ Функции bin и oct используйте для проверки своего
результата, а не для решения.
   <br>
Дополнительно:
    - ✔ Попробуйте избежать дублирования кода
в преобразованиях к разным системам счисления
    - ✔ Избегайте магических чисел
    - ✔ Добавьте аннотацию типов где это возможно
4. [Задание 4](Seminar_2/Task_2_4.py)
    - Напишите программу, которая вычисляет площадь
круга и длину окружности по введённому диаметру.
    - ✔ Диаметр не превышает 1000 у.е.
    - ✔ Точность вычислений должна составлять
не менее 42 знаков после запятой.
5. [Задание 5](Seminar_2/Task_2_5.py)
   - Напишите программу, которая решает квадратные уравнения даже если дискриминант отрицательный.
   - ✔ Используйте комплексные числа
для извлечения квадратного корня.
6. [Задание 6](Seminar_2/Task_2_6.py)
   - Напишите программу банкомат.
   - ✔ Начальная сумма равна нулю
   - ✔ Допустимые действия: пополнить, снять, выйти
   - ✔ Сумма пополнения и снятия кратны 50 у.е.
   - ✔ Процент за снятие — 1.5% от суммы снятия, но не менее 30 и не более 600 у.е.
   - ✔ После каждой третей операции пополнения или снятия начисляются проценты - 3%
   - ✔ Нельзя снять больше, чем на счёте
   - ✔ При превышении суммы в 5 млн, вычитать налог на богатство 10% перед каждой
   - операцией, даже ошибочной
   - ✔ Любое действие выводит сумму денег
7. [ДОМАШНЯЯ РАБОТА](Homework/Seminar_2)
   - Напишите программу, которая получает целое число и возвращает его шестнадцатеричное
строковое представление. Функцию hex используйте для проверки своего результата.
   - ✔ Напишите программу, которая принимает две строки вида “a/b” — дробь с числителем и знаменателем.
Программа должна возвращать сумму и *произведение дробей. Для проверки своего
кода используйте модуль fractions.
   
# СЕМИНАР 3 Коллекции
1. [Задание 1](Seminar_3/Task_3_1.py)
    - Вручную создайте список с целыми числами, которые повторяются. Получите новый список, который содержит
уникальные (без повтора) элементы исходного списка.
    - ✔ *Подготовьте два решения, короткое и длинное, которое
не использует другие коллекции помимо списков
2. [Задание 2](Seminar_3/Task_3_2.py)
    - Пользователь вводит данные. Сделайте проверку данных и преобразуйте если возможно в один из вариантов ниже:
    - ✔ Целое положительное число
    - ✔ Вещественное положительное или отрицательное число
    - ✔ Строку в нижнем регистре, если в строке есть хотя бы одна заглавная буква
    - ✔ Строку в нижнем регистре в остальных случаях
3. [Задание 3](Seminar_3/Task_3_3.py)
    - Создайте вручную кортеж содержащий элементы разных типов.
    - ✔ Получите из него словарь списков, где: ключ — тип элемента, значение — список элементов данного типа
4. [Задание 4](Seminar_3/Task_3_4.py)
    - Создайте вручную список с повторяющимися элементами.
    - ✔ Удалите из него все элементы, которые встречаются дважды.
5. [Задание 5](Seminar_3/Task_3_5.py)
   - Создайте вручную список с повторяющимися целыми числами.
   - ✔ Сформируйте список с порядковыми номерами нечётных элементов исходного списка.
   - ✔ Нумерация начинается с единицы.
6. [Задание 6](Seminar_3/Task_3_6.py)
   - Пользователь вводит строку текста. Вывести каждое слово с новой строки.
   - ✔ Строки нумеруются начиная с единицы.
   - ✔ Слова выводятся отсортированными согласно кодировки Unicode.
   - ✔ Текст выравнивается по правому краю так, чтобы у самого длинного слова был один пробел между ним и номером строки.
7. [Задание 7](Seminar_3/Task_3_7.py)
   - Пользователь вводит строку текста.
   - ✔ Подсчитайте сколько раз встречается каждая буква в строке без использования метода count и с ним.
   - ✔ Результат сохраните в словаре, где ключ — символ, а значение — частота встречи символа в строке.
   - ✔ Обратите внимание на порядок ключей. Объясните почему они совпадают или не совпадают в ваших решениях.
8. [Задание 8](Seminar_3/Task_3_8.py)
   - Три друга взяли вещи в поход. Сформируйте словарь, где ключ — имя друга, а значение —  кортеж вещей. Ответьте на вопросы:
   - ✔ Какие вещи взяли все три друга
   - ✔ Какие вещи уникальны, есть только у одного друга
   - ✔ Какие вещи есть у всех друзей кроме одного  и имя того, у кого данная вещь отсутствует
   - ✔ Для решения используйте операции  с множествами. Код должен расширяться  на любое большее количество друзей.
9. [ДОМАШНЯЯ РАБОТА](Homework/Seminar_3/Task_3_9.py)
   - Дан список повторяющихся элементов. Вернуть список  с дублирующимися элементами. В результирующем списке не должно быть дубликатов.
   - ✔ В большой текстовой строке подсчитать количество встречаемых слов и вернуть 10 самых частых. Не учитывать знаки препинания
и регистр символов. За основу возьмите любую статью из википедии или из документации к языку.
   - ✔ Создайте словарь со списком вещей для похода в качестве ключа и их массой в качестве значения. Определите какие
вещи влезут в рюкзак передав его максимальную грузоподъёмность. Достаточно вернуть один допустимый вариант.
   - ✔ *Верните все возможные варианты комплектации рюкзака.

# СЕМИНАР 4 Функции
1. [Задание 1](Seminar_4/Task_4_1.py)
    -  Напишите функцию, которая принимает строку текста. Вывести функцией каждое слово с новой строки.
    - ✔ Строки нумеруются начиная с единицы.
    - ✔ Слова выводятся отсортированными согласно кодировки Unicode.
    - Текст выравнивается по правому краю так, чтобы у самого длинного слова был один пробел между ним и номером строки.
2. [Задание 2](Seminar_4/Task_4_2.py)
    - Напишите функцию, которая принимает строку текста.
    - ✔ Сформируйте список с уникальными кодами Unicode каждого символа введённой строки отсортированный по убыванию.
3. [Задание 3](Seminar_4/Task_4_3.py)
    - Функция получает на вход строку из двух чисел через пробел.
    - ✔ Сформируйте словарь, где ключом будет символ из Unicode, а значением — целое число.
    - ✔ Диапазон пар ключ-значение от наименьшего из введённых пользователем чисел до наибольшего включительно.

4. [Задание 4](Seminar_4/Task_4_4.py)
    - Функция получает на вход список чисел.
    - ✔ Отсортируйте его элементы in place без использования встроенных в язык сортировок.
    - ✔ Как вариант напишите сортировку пузырьком. Её описание есть в википедии.
5. [Задание 5](Seminar_4/Task_4_5.py)
   - Функция принимает на вход три списка одинаковой длины:
   - ✔ имена str,
   - ✔ ставка int,
   - ✔ премия str с указанием процентов вида «10.25%».
   - ✔ Вернуть словарь с именем в качестве ключа и суммой премии в качестве значения.
   - ✔ Сумма рассчитывается как ставка умноженная на процент премии. 
6. [Задание 6](Seminar_4/Task_4_6.py)
   - Функция получает на вход список чисел и два индекса.
   - ✔ Вернуть сумму чисел между между переданными индексами.
   - ✔ Если индекс выходит за пределы списка, сумма считается до конца и/или начала списка.

7. [Задание 7](Seminar_4/Task_4_7.py)
   - Функция получает на вход словарь с названием компании в качестве ключа
и списком с доходами и расходами (3-10 чисел) в качестве значения.
   - ✔ Вычислите итоговую прибыль или убыток каждой компании. Если все компании
прибыльные, верните истину, а если хотя бы одна убыточная — ложь.
8. [Задание 8](Seminar_4/Task_4_8.py)
   - Создайте несколько переменных заканчивающихся и не оканчивающихся на «s».
   - ✔ Напишите функцию, которая при запуске заменяет содержимое переменных
оканчивающихся на s (кроме переменной из одной буквы s) на None.
   - ✔ Значения не удаляются, а помещаются в одноимённые переменные без s на конце.
9. [ДОМАШНЯЯ РАБОТА](Homework/Seminar_4)
   - Напишите функцию для транспонирования матрицы
   - ✔ Напишите функцию принимающую на вход только ключевые
параметры и возвращающую словарь, где ключ — значение
переданного аргумента, а значение — имя аргумента. Если
ключ не хешируем, используйте его строковое представление.
   - ✔ Возьмите задачу о банкомате из семинара 2. Разбейте её
на отдельные операции — функции. Дополнительно сохраняйте
все операции поступления и снятия средств в список.
