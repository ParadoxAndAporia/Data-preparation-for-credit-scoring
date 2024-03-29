# Исследование надёжности заёмщиков

## Описание проекта

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Описание данных

- children — количество детей в семье
- days_employed — общий трудовой стаж в днях
- dob_years — возраст клиента в годах
- education — уровень образования клиента
- education_id — идентификатор уровня образования
- family_status — семейное положение
- family_status_id — идентификатор семейного положения
- gender — пол клиента
- income_type — тип занятости
- debt — имел ли задолженность по возврату кредитов
- total_income — ежемесячный доход
- purpose — цель получения кредита

## Вывод по итогам исследования
&nbsp; &nbsp; В ходе исследования мы выяснили, что с увеличением количества детей уменьшается вероятность погашения кредита в срок, семейное положение влияет на погашение кредита. (При этом гипотеза о наличии связи между возрастом и вероятностью погашения кредита не подтвердилась.)

&nbsp; &nbsp; Также, вопреки ожиданиям, наиболее обеспеченная группа заемщиков не является наиболее надежной.  А обеспечение исполнения кредитных обязательств залогом - ипотекой - приводит к наименьшим просрочкам по кредитам. 

&nbsp; &nbsp; Любопытно, что примерно с такой же дисциплинированностью, что  и ипотечники, молодожены погашают кредиты, взятые на проведение свадьбы.

