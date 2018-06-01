# hw9
## 1. Удалить все пустые строки.
### Чтобы удалить все пустые строки , я использовала данное регулярное выражение \n\r , затем заменила на \0 .
![](https://pp.userapi.com/c824701/v824701563/14c116/3z9N2x8wa20.jpg)
## 2. Найти всех князей и города, имя и название которых оканчивается на "слав". В выдаче должны быть такие слова как "Ярославля, Ростиславъ, Ростиславу, Переяславлъ" и т.п. Но не должно быть "славу, выславше" и т.п. 
### Для выполнения данного задания я использовала следующее регулярное выражение [А-Я]+\w+слав+\w* Всего нашла упоминаний о князьях: 592
![](https://pp.userapi.com/c846417/v846417284/68346/eeSnpmntUUo.jpg)
## 3. Найти все упоминания Новгорода. Учтите, что написание может быть разным . В выдаче должны быть такие слова как "Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду". 
## Для выполнения данного задания я использовала следующее регулярное выражение Нов(ѣ|ъ|у|а)?город(цю)?[^\s.,\?!:;-]* Всего нашла упоминаний Новгорода: 58
![](https://pp.userapi.com/c845522/v845522924/6db1d/QsvFIa6MSdA.jpg)
