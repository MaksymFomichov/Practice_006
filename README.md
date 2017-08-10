# Practice_006
## Задание 1
Построить три класса (базовый и 2 потомка), описывающих некоторых работников с почасовой оплатой (один из потомков) и фиксированной оплатой (второй потомок).
Все работники должны иметь имя и фамилию. 

Описать в базовом классе абстрактный метод для расчета месячной заработной платы. 

Для «повременщиков» формула для расчета такова: «месячная заработная плата = 20.8 * 8 * почасовую ставку»

Для работников с фиксированной оплатой «месячная заработная плата = фиксированной месячной оплате».
## Задание 2
Создать класс - Company.
Компания хранит массив своих работником. 
Написать функцию расчета денежных затрат компании в месяц на выплату зарплат работникам.

Написать функцию которая выводит информацию о всех работниках в консоль.

Компания должна уметь сохранять все свои данные в файл. И уметь загружать данные с файла при запуске. 
Если файл поврежден / отсутствует / имеет некорректный формат, программа должна проигнорировать его и запуститься по умолчанию минуя загрузку данных с файла.
## Задание 3
Добавить класс нового типа сотрудников - фрилансеров. Фрилансер не всегда работает 8 часов в день. У него есть договоренное кол-во часов работы в день.

Для фрилансеров формула расчета такова «месячная заработная плата = 20.8 * часов работы в день * почасовую ставку»

Добавить в компанию несколько фрилансеров и пересчитать затраты компании.
## Задание 4
Добавить компании новую бугалтерскую возможность - сортировать работников по месячной заработной плате. Требуется сортировка от высокой к низкой и еще одна сортировку в обратном порядке.
