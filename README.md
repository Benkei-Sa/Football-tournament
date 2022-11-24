# Football-tournament

🤔 Футбольный турнир
Четыре команды (A, B, C и D) сыграли футбольный турнир. Каждая команда сыграла с каждой
по одному разу, так что всего прошло 6 матчей. Рассчитайте, сколько очков получила каждая
команда.

Победа приносит 3 очка, ничья — 1, поражение — 0.

Результаты игр подаются на вход программы строкой вида:

ABW DCD DAW CBL BDL ACW
Каждая тройка букв означает одну игру. Внутри тройки первая буква — название первой команды,
вторая буква — название второй, третья — код результата (W — первая выиграла, L — первая 
проиграла, D — ничья).

Код, который считывает и парсит результаты игр, уже написан. Ваша задача — реализовать 
структуры данных и логику подсчета результата.

Sample Input:
ABW DCD DAW CBL BDL ACW

Sample Output:
A6 B3 C1 D7 