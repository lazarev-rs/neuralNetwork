Задача нейронной сети — решить, что делать персонажу, исходя из 3х параметров:

    Количество здоровья (от 1 до 100)
    Наличие оружия
    Количество врагов

В зависимости от результата, может быть принято одно из следующих решений:

    Атаковать
    Красться
    Убегать
    Ничего не делать


##### Примеры:
##### Здоровье	Оружие	Враги	Решение

    50	1	1	Атаковать
    90	1	2	Атаковать
    80	0	1	Атаковать
    30	1	1	Красться
    60	1	2	Красться
    40	0	1	Красться
    90	1	7	Убегать
    60	1	4	Убегать
    10	0	1	Убегать
    60	1	0	Ничего не делать
    100	0	0	Ничего не делать