# Влияние хайпа на IPO и оценку компаний-единорогов

___

![Визуализация 1](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/unicorns%20visuals/1BU.png)
___

## Данные, использованные для исследования:
- Yahoo Finance для исторических цен акций
- Комиссия по ценным бумагам и биржам США для проспектов IPO
- Crunchbase для списка компаний-единорогов и информации о медиа-освещении

## Краткое описание:
- **Компании-единороги** — это инновационные компании, достигшие оценки в $1 миллиард от венчурных фондов до достижения такой оценки на рынке (например, Uber, Facebook и т.д.).
- Компании-единороги создаются со стратегией blitz-scaling, которая фокусируется на росте, а не на эффективности.
- Количество таких компаний резко возросло за последнее десятилетие из-за стремления венчурных фондов получить "единорога" в своем портфеле, а также вследствие множества небольших инвестиций в технологические стартапы.

![Визуализация 2](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/1.png)

- Компании-единороги, убыточные на момент IPO, сегодня привлекают больше средств, чем прибыльные компании во время эпохи Dotcom.

![Визуализация 3](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/2.png)

- Для исследования я изучил 75 компаний, которые вышли на NASDAQ и NYSE: проспекты IPO, исторические данные акций, информацию с Crunchbase.

![Визуализация 4](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/3.png)

## Хайп: положительное и отрицательное влияние

- Хайп влияет на оценку и может быть измерен в первый день торгов, анализируя недооценку, а также в первые месяцы после IPO, анализируя результаты акций.

- **Недооценка** — это ситуация, когда компания занижает стоимость своих акций перед IPO, а цены резко взлетают в первый день торгов. Это выгодно для инвесторов, но плохо для единорогов, так как они теряют деньги, которые могли бы получить при более высокой начальной цене. Недооценка может быть измерена с помощью MAIR (Market Adjusted Initial Return).

![Визуализация 5](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/4.png)

- Существует ряд факторов, увеличивающих или уменьшающих недооценку для компаний-единорогов, которые я выявил с помощью множественной линейной регрессии:

![Визуализация 6](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/5.png)

- С помощью теста Манна-Уитни я также выяснил, что компании, занимающиеся разработкой программного обеспечения, более подвержены недооценке.

![Визуализация 7](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/6.png)

- Методом исследования событий можно измерить хайп после IPO, анализируя аномальные доходности. Этот метод использует математический/финансовый подход к прогнозированию цен акций, после чего результаты прогнозов сравниваются с фактическими доходностями акций. Я использовал CAAR (Cumulative Average Abnormal Returns) для группировки компаний-единорогов в зависимости от количества новостных статей о них до даты IPO. Во всех случаях t-статистика демонстрирует отклонение от нуля.

![Визуализация 8](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/7.png)

- Как видно, в среднем хайп достигает пика на третий месяц. Стоит отметить, что чрезмерный хайп также снижает аномальные доходности, так как хайп может быть как положительным, так и отрицательным. Я сравнил распределение CAR (Cumulative Abnormal Returns) между группами в период пика.

![Визуализация 9](https://github.com/Denis1gn/portfolio/blob/main/Research/Master's%20Degree/visuals/8.png)

- С помощью статистического теста Краскела–Уоллиса я продемонстрировал, что компании с низким уровнем хайпа имели иное распределение CAR по сравнению с хайповыми компаниями.

- В результате видно, что хайп может быть как полезным, так и вредным для компаний-единорогов. Хотя они теряют деньги из-за недооценки, их акции также получают поддержку благодаря хайпу.

## Заключение

Этот проект демонстрирует, как хайп влияет на IPO и последующую оценку компаний-единорогов, основываясь на анализе данных и моделировании финансовых показателей.
