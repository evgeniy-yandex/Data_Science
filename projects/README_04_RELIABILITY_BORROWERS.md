# Яндекс Практикум. Курс "Data Science". Проект: Исследование надёжности заёмщиков

## Первая часть
- Импортировали библиотеку pandas. Считали данные из csv-файла в датафрейм. 
- Вывели и изучили основную информацию о датафрейме. 
- Изучили и заполнили пропущенные значения.
- Изучили и исправили аномальные значения.
- Откорректировали типы данных.
- Обработали неявные дубликаты.
- Провели категоризацию данных.

## Вторая часть  
По результатам исследования отмечено:
1.	У бездетных семей задолженность реже встречается, чем у семей с детьми.
2.	При довольно ровных результатах для семей с 1,2 и 4 детьми наблюдается резкое снижение просрочки займа для семей с 3 детьми! Скорее всего это объясняется господдержкой многосемейных и целевыми выплатами на 3-го ребёнка.
4.	По вероятности просрочки займов можно выделены 3 группы граждан:
* люди, потерявшие супруга в силу каких-то трагических обстоятельств,
* люди, живущие в браке или находящиеся в разводе,
* люди, не имеющие официальных семейных обязательств.
4.	Самыми надёжными заёмщиками являются люди, пережившие трагедию с потерей супруга. Кроме более высокой финансовой дисциплины, возможно, расплачиваться по кредитам им помогают:
* совместные накопления,
* пенсии на потерю супруга,
* наследство,
* ещё какие-то выплаты...
5.	Люди, не имеющие семейных обязательств, относятся к группе с наибольшим риском по образованию финансовой задолженности.
6.	Всех заемщиков можно объединить в 3 группы
* Надежные.
  Сверхбогатые (с доходом выше 500000 рублей в месяц) + бедные (с доходом до 50000 руб/мес).
  Они менее других имеют проблемы с выплатой займов.
* Безнадежные.
  Люди со средним достатком (50 000 - 500 000 руб/мес). 
  Эти заемщики чаще других люднй набирают долги по погашению кредитов.
* Вполне надежные.
  Это люди, зарабатывающие 200 - 500 тыс рублей в месяц. 
  По уровню просрочек кредитов они находятся не по середине между предудущими двумя группами, а ближе к надежным.
7.	По целям кредитования можно выделить 2 группы с различными значениями появления задолженностей.
* С меньшим риском образования задолженности. К ней можно отнести заёмщиков для операций с недвижимостью и новобрачных.
* С повышенным уровнем получения задолженности. В такую группу попадают люди, берущие кредиты на получение образования и операции с автомобилем.
8.	Выдача кредита на операции с недвижимостью - наименее рисковая.
9.	Удивляет довольно большое (около 8%) количество должников по кредитам на проведение свадьбы. 

Общий вывод.
Общие выводы иногда могут вызвать улыбку, но, главное, они не предсказывают аномально опасных типов заёмщиков:
1.	Идеальный заёмщик:
* Бездетный человек, потерявший супруга,
* живущий с доходом свыше полумиллиона в месяц или, наоборот, на пенсию/пособие,
* Проводящий операции с недвижимостью (наверное, для богатых людей) или готовящийся к свадьбе.
2.	Самый опасный заёмщик:
* одинокий человек, не знавший горечи утраты супруга,
* обременённый детьми,
* со средним достатком,
* покупающий автомобиль.
3.	Чаще всего кредиты оформляют семейные пары (возможно, могут поручиться друг за друга) с детьми, со средним доходом (100-200 тыс руб) на покупку недвижимости.
4.	Реже оформляют кредиты люди, потерявшие супруга, с доходом или до 1 млн руб.мес или до 50 тыс руб.мес. на покупку недвижимости или на новую свадьбу. Практически редчайший случай, когда у них ещё и 5 детей.
5.	По различным факторам (уровень дохода, наличие детей, семейное положение и целям кредитования) отличие максимального и минимального вероятности возникновения задолженности по выплате кредита не превышает 20-30% относительных. Таким образом, среди перечисленных факторов нет таких, которые могли бы аномально увеличить риск невозврата кредита.

[Вернутся к общему списку](../README.md)