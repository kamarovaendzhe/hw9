# Домашнее задание №9 
### Первоначальный вид задания
![](https://github.com/kamarovaendzhe/hw9/blob/master/Первоначальный%20вид.PNG?raw=true)
## _Задание 1_
### Использовала регулярное выражение: \n\r 
### Заменила все вхождения на: \0
### В итоге удалились все пустые строки
![](https://github.com/kamarovaendzhe/hw9/blob/master/task_1.png?raw=true)
![](https://github.com/kamarovaendzhe/hw9/blob/master/task_1_1.png?raw=true)
## _Задание 2_
### Использовала регулярное выражение: \b[А-Я][а-я]*слав[а-я]{0,3}\b 
### Всего упоминаний о князьях и городах нашла: 561
![](https://github.com/kamarovaendzhe/hw9/blob/master/task_2.png?raw=true)
![](https://github.com/kamarovaendzhe/hw9/blob/master/task_2_1.png?raw=true)
## _Задание 3_
### Использовала регулярное выражение: Н\D?о\D?в\D?г\D?о\D?р\D?о\D?д\w*
### Всего упоминаний Новгорода нашла: 59
![](https://github.com/kamarovaendzhe/hw9/blob/master/task_3.png?raw=true)
![](https://github.com/kamarovaendzhe/hw9/blob/master/task_3_1.png?raw=true)
## _Бонусное задание_
### Испоьзовала регулярное выражение: (\.|\,|\:|\;|\)|\».|\})
### Заменила все вхождения на: \1  (после выражения "\1" поставила пробел)
![](https://github.com/kamarovaendzhe/hw9/blob/master/bonus_1.png?raw=true)
![](https://github.com/kamarovaendzhe/hw9/blob/master/bonus_1_1.png?raw=true)
### Все троеточия разделились пробелами, поэтому использовала дополнительное регулярное выражение: \. . . (в данном регулярном выражении на сайте гитхаб не ставится бэкслэш и пробелы между точками, поэтому разъясню свою формулу словами: "бэкслеш,точка,пробел,точка,пробел,точка, пробел")
### Заменила все вхождения на: \... ("бэкслэш, троеточие")
![](https://github.com/kamarovaendzhe/hw9/blob/master/bonus_2.png?raw=true)
![](https://github.com/kamarovaendzhe/hw9/blob/master/bonus_2_1.png?raw=true)
