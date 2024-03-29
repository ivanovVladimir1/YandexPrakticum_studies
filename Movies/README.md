## Исследование рынка российского кинопроката

Изучить рынок российского кинопроката и выявить текущие тренды.  
Провести анализ, насколько  фильмы, которые получили государственную поддержку, интересны зрителю. 

#### Используемые библиотеки
pandas matplotlib seaborn

## Общий вывод

Проведен анализ рынка российского кинопроката. Входящие данные объединены в один датафрейм на основании номера прокатного удостоверения.

Исследована динамика по количеству картин. За рассматриваемый период количество фильмов ежегодно растет, за исключением 2017 г. Также с годами растет и раскрываемость финансовых показателей картин.

Российский кинематограф не научился окупать себя. Большинство фильмов не окупаются; медианный убыток составляет 40 млн руб.

Лишь в 2017 и 2018 г. суммарные сборы превысили расходы на производство.

Средний рейтинг - 6. Рейтинг не оказывает заметного влияния на сборы и доход картин в прокате.

Уровень поддержки составляет 60-70 % бюджета фильма чаще всего. Наиболее крупно поддерживаемые жанры - комедии и драмы.

Рекомендации
При сборе данных:
* унифицировать написание названий фильмов (например название пробел часть), исключить дополнения (разнообразные "по мотивам..." и подобные);
* тип фильма давать на выбор из подготовленного списка (выпадающий список или подобное);
* унифицировать персоналии (Имя Фамилия либо Инициалы Фамилия);
* возрастную категорию ограничить числом;
* рейтинг обозначать в общепринятой манере (дробное число с одним знаком после запятой).
