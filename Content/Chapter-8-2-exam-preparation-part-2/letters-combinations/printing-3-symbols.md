#### Отпечатване на комбинации от три символа

Използваме **цикъл**, който минава през **всички символи** от началната до крайната буква включително. На **всяка итерация** на **първия** цикъл пускаме **втори** със същите параметри (но **само ако** буквата на първия цикъл е валидна, т.е. не съвпада с тази, която трябва да изключим по условие). На всяка итерация на **втория** цикъл пускаме още **един** със **същите параметри** и същата **проверка**. По този начин ще имаме три вложени цикъла, като в тялото на **последния** ще принтираме символите.

![](/assets/chapter-8-2-images/06.Letters-03.png)

Нека не забравяме, че се изисква от нас да принтираме и **общия брой валидни комбинации**, които сме намерили, както и че те трябва да се принтират на **същия ред**, разделени с интервал.

### Testing in the Judge System

Тествайте решението си тук: [https://judge.softuni.bg/Contests/Practice/Index/517#5](https://judge.softuni.bg/Contests/Practice/Index/517#5).