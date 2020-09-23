# Algorithmic_Tasks_Cpp

Ограничение времени	1 секунда.
Ограничение памяти	64Mb.
Ввод:	стандартный ввод или input.txt.
Вывод:	стандартный вывод или output.txt.

 #1
"Добавление".

Условие:
Дан неориентированный граф. Определить минимальное количество ребер, после добавления которых граф станет связным. Вывести -1 если ответа не существует.

Формат ввода:
В первой строке два числа N (1 ≤ N ≤ 10^4) и M (0 ≤ M ≤ 10^5) — количество вершин и ребер соответственно.
Следующие M описывают ребра: пара чисел U, V (1 ≤ U, V ≤ N) — номера вершин, соединенных ребром.

Формат вывода:
Вывести ответ на задачу. Если ответа не существует, то вывести -1.

#2
"Простая задача".

Условие:
Дана последовательность целых чисел. Найти максимальное число, которое может быть получено путем перемножения двух любых чисел последовательности.

Формат ввода:
В первой строке содержится число N — количество чисел в последовательности (2 ≤ N ≤ 10^5).
Во второй строке содержатся числа A1 A2 ... AN — элементы последовательности, разделенные пробелом (|Ai| ≤ 10^9).

Формат вывода:
Выведите максимальное число, которое может быть получено путем перемножения двух любых чисел последовательности.

#3
 "Путешествие с конём".

Условие:
Размеры прямоугольной размеченной квадратами доски n × m. В нижнем левом квадрате доски (1,1) находится шахматный конь. Конь может ходить только согласно шахматным правилам – движение может быть двумя квадратами горизонтально и затем одним вертикально, или двумя квадратами вертикально и одним горизонтально. Например, если n=4 и m=3, и конь находится в квадрате (2,1), то следующим может быть ход (1,3) или (3,3) или (4,2). Для заданных положительных целых значений n, m, i и j требуется определить минимальное необходимое количество ходов коня для перемещения из начальной позиции (1,1) в квадрат (i,j).

Формат ввода:
В единственной строке заданы четыре целых числа n m i j — размеры доски и координаты конечного квадрата (1 ≤ n, m ≤ 100, 1 ≤ i ≤ n, 1 ≤ j ≤ m).

Формат вывода:
В единственной строке выведите минимальное количество ходов для перемещения или "NEVAR" если это невозможно.

#4
"Кратчайший путь".

Условие:
Задан связный неориентированный взвешенный граф G. В графе возможно наличие нескольких ребер между одной и той же парой вершин. Найдите вес кратчайшего пути между двумя заданными вершинами A и B.

Формат ввода:
Первая строка содержит целое число N (1 ≤ N ≤ 10^5)  — количество вершин графа.
Вторая строка содержит целое число M (1 ≤ M ≤ 10^6)  — количество ребер графа.
В каждой из следующих M строк содержатся ровно три числа A, B, C (1 ≤ A, B ≤ N, 1 ≤ C ≤ 10^6). Эти числа описывают ребро, соединяющее вершины с номерами A и B и имеющее вес C.
Последние две строки содержат целые числа A и B (1 ≤ A, B ≤ N) - начальную и конечную вершины пути. Вершины нумеруются последовательными натуральными числами от 1 до N.

Формат вывода:
Единственная строка выходного файла должна содержать одно целое число, равное весу кратчайшего пути между вершинами A и B в графе G.

#5
"Шахматная игра".

Условие:
Дано поле N × M. На нем расположены две ладьи, координаты каждой (X1, Y1) и (X2, Y2) соответственно. Ладья ходит по классическим правилам шахмат: за один ход может переместиться в любую клетку, расположенную на одной вертикали либо горизонтали. Одна ладья может сбить другую, если та находится с ней на одной горизонтали либо вертикали.
Основное отличие от классических правил: ладья не может переместиться в клетку, если во время передвижения к ней она станет на клетку, которая находится под боем другой ладьи. У первого игрока в распоряжении первая ладья, а у второго —вторая. Игроки ходят по очереди, ход пропускать нельзя. Первым ходит первый игрок. Проигрывает тот, кому некуда ходить (куда бы ни пошел — собьют). Определите кто победит при оптимальной игре обоих.

Формат ввода:
В первой строке через пробел вводятся 6 целых чисел N M X1 Y1 X2 Y2 (2 ≤ N, M ≤ 50, 1 ≤ X1, X2 ≤ N, 1 ≤ Y1, Y2 ≤ M, X1 ≠ X2 или Y1 ≠ Y2).

Формат вывода:
Выведите YES, если победит первой игрок, иначе NO.

#6
"Максимальный неподпалиндром".

Условие:
В заданной строке S найти максимальную по длине подстроку, которая не является палиндромом.

Формат ввода:
На вход задается строка S, состоящая из строчных букв латинского алфавита (1 ≤ |S| ≤ 10^5).

Формат вывода:
Выведите одно целое число — длина максимального непалиндрома. Если такой подстроки не существует, то выведите -1.

#7
"Инвертирование".

Условие:
Дана строка S и Q запросов. Запрос представляет собой пару чисел L и R — промежуток строки S, на котором нужно инвертировать регистр символов. Требутеся найти строку S после выполнения всех запросов.

Формат ввода:
В первой строке задается строка S, состоящая из строчных и прописных букв латинского алфавита (1 ≤ |S| ≤ 10^5).
Во второй строке задается число Q — количество запросов (0 ≤ Q ≤ 10^6).
В следующих Q строках задаются запросы парой целых чисел Li Ri (1 ≤ Li, Ri ≤ N).

Формат вывода:
Выведите строку S после выполнения всех запросов.

#8
"Сумма на дереве".

Условие:
Дано дерево. Определить сумму весов всех кратчайших расстояний между каждой парой вершин.

Формат ввода:
В первой строке число N (1 ≤ N ≤ 10^5) — количество вершин.
Следующие N - 1 строк описывают ребра: тройка чисел A, B, C — номера вершин, соединенных ребром и вес ребра соответственно (0 ≤ C ≤ 10^6).

Формат вывода:
Вывести ответ на задачу по модулю 10^7+7.

#9
"Большой куш".

Условие:
Известный фокусник Донни разбогател на очень простой игре. Он играл в нее на деньги с самыми богатыми и знаменитыми личностями, но никто ни разу не смог его обхитрить. И тут очередь дошла до вас. Вы белорусский бизнесмен и хотите удвоить свое состояние. Обыграйте Донни и сорвите куш! Так же вы можете отказаться от игры, если, при виде начальной позиции, на вас нападет плохое предчувствие.
Правила игры следующие: Изначально дано число X. За один ход разрешается отнять от числа X любую цифру, кроме 0, которая входит в число X. Проигрывает тот, кто не может ходить, то есть когда будет получено число 0.

Формат ввода:
В первой строке задается число X — начальное число для игры (0 ≤ X ≤ 10^10).

Формат вывода:
Выведите цифру первого хода, которая приведет вас к победе, иначе выведите NO, если хотите отказаться от игры.

#10
"Удаление".

Условие:
Дан неориентированный граф. Определить минимальное количество ребер, после удаления которых между каждой парой вершин будет существовать только один маршрут (без повторений в нем ребер). Вывести -1, если ответа не существует.

Формат ввода:
В первой строке два числа N (1 ≤ N ≤ 10^4) и M (1 ≤ M ≤ 10^5) — количество вершин и ребер соответственно.
Следующие M описывают ребра: пара чисел U, V — номера вершин, соединенных ребром.

Формат вывода:
Вывести ответ на задачу. Если ответа не существует, то вывести -1.

#11
"Выравнивание".

Условие:
Дана последовательность Ai, состоящая из N целых чисел. За одно действие можно зафиксировать произвольный промежуток одинаковых элементов последовательности и увеличить все элементы этого промежутка на 1. Необходимо за минимальное количество действий уравнять все элементы.

Формат ввода:
В первой строке вводится число N (1 ≤ N ≤ 10^5). Во второй строке вводятся элементы последовательности Ai (0 ≤ Ai ≤ 10^9).

Формат вывода:
В единственной строке выведите одно число — минимальное количество действий, которое необходимо выполнить для того, чтобы уравнять все элементы последовательности.

#12
"Следующее".

Условие:
Дано число X. Надо найти наименьшее число большее, чем X, которое может быть получено из X перестановкой цифр.

Формат ввода:
В первой строке задается целое число X (1 ≤ X < 10^6).

Формат вывода:
Если ответ не существует, то выведите -1, иначе искомое число.

#13
"1087388483"

Условие:
Дана последовательность из N целых положительных чисел. Требуется определить можно ли путем перемножения некоторых чисел последовательности получить число 1087388483.

Формат ввода:
В первой строке содержится число N (1 ≤ N ≤ 10^5).
В следующих N строках содержатся Ai — элементы последовательности (0 ≤ Ai ≤ 2 × 10^9).

Формат вывода:
Если можно получить данное число, тогда выведите YES, иначе NO.

#14
"Високосный"
Условие:
Високосный год — год в юлианском и григорианском календарях, продолжительность которого равна 366 дням — на одни сутки больше продолжительности обычного, невисокосного года. В юлианском календаре високосным годом является каждый четвёртый год, в григорианском календаре из этого правила есть исключения. Год в григорианском календаре является високосным, если он кратен 4 и при этом не кратен 100, либо кратен 400. Определите, является ли заданный год високосным в григорианском календаре.

Формат ввода:
В первой и единственной строке задается целое число Y — год, который нужно проверить (2000 ≤ Y ≤ 9999).

Формат вывода:
Если заданный год високосный, то выведите YES, иначе — NO.

#15
"Инверсии".

Условие:
Перестановкой чисел 1, 2, 3, ..., N  назовем такую последовательность А длины N, что 1 ≤ Ai ≤ N, и все числа последовательности различны.
Инверсией в пeрестановке A размера N называется всякая пара индексов (i, j) такая, что i < j и Ai > Aj.
В данной задаче необходимо найти число инверсий в заданной перестановке.

Формат ввода:
В первой строке задано число N (1 ≤ N ≤ 10^6). Во второй строке задана перестановка чисел.

Формат вывода:
Выведите одно целое число — количество инверсий во входной перестановке.
