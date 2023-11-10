# FiniteAutomaton

Задание:
  1. Разработать распознающий КА для цепочек определенного в задании регулярного языка над заданным алфавитом и реализовать его в виде подпрограммы.
  2. Разработать программу поиска цепочек этого языка в последовательности символов, используя подпрограмму пункта 1. 
 Вход: последовательность символов алфавита регулярного языка задания.
 Выход: последовательность строк формата номер: цепочка номер – номер позиции начала цепочки языка в последовательности символов цепочка – найденная цепочка языка в последовательности символов.
 Если цепочек языка не найдено, то на выходе отображается «цепочек не найдено»

Описание регулярного языка над алфавитом {a,b,\~}:

Строка символов a,\~,b, начинающаяся с префикса \~ и заканчивающаяся суффиксом \~, между которыми располагается последовательность символов a,b, состоящая из повторяющихся групп символов: четное число (нуль не считаем четным) подряд идущих символов a, за которыми следует один символ b, или нечетное число подряд идущих символов a, за которыми следует два символа b (пример: \~\~ или \~abbaaaabaaabb\~). 

Замечание: если цепочки языка начинаются и заканчиваются одинаковым символом, то завершающий символ считать началом следующей возможной цепочки языка в последовательности символов. Если цепочки языка заканчиваются последовательностью символов, то в этой последовательности могут существовать начальные символы для начальной последовательности символов следующей возможной цепочки языка. Например, цепочки языка ограничены последовательностями abc и cab, то последние два символа ab последовательности cab могут начинать последовательность abc.
