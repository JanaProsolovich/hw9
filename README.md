# hw9

# Регулярные выражения

1. скопировала и вставила текст

![](https://github.com/JanaProsolovich/hw9/blob/master/вставить%20текст.PNG)
**Задание номер 1**

убрала все пробелы, используя данное выражение- 
*(\n\n) заменила все вхождения на \n.*

![](https://github.com/JanaProsolovich/hw9/blob/master/убрала%20пробелы.PNG)
**Задание номер 2**

Нашла всех князей и города, имя и название которых оканчивается на "слав", используя данное выражение
*[А-Я][а-яё]*слав[^\s.,\?!:;]*

![](https://github.com/JanaProsolovich/hw9/blob/master/ярослав.PNG)

**Задание номер 3**

 Нашла все упоминания Новгорода. В выдаче получились такие слова как "Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду". 
 Регулярное выражение- 
 
*(Нов(ѣ|ъ|[а-яё])?город([а-яё]*)?)[^\s.,\?|:;]**

![](https://github.com/JanaProsolovich/hw9/blob/master/3%20задание.PNG)
