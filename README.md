# Исследование источников траффика и определение перспективных когорт клиентов для Яндекс.Афиши

## Задача

Заказчик — отдел маркетинговой аналитики Яндекс.Афиши. Необходимо проанализировать, какие источники трафика наименее выгодны и дать рекомендации по распределению маркетингового бюджета. 

Анализ проводится для периода с июня 2017 по конец мая 2018 года.

Метрики для расчета: DAU, WAU, MAU, ASL, Daily Sessions, Retention Rate, LTV, CAC, ROMI, Bounce Rate

## Данные

Входные данные от компании:
- лог сервера с данными о посещениях сайта Яндекс.Афиши;
- выгрузка всех заказов за этот период;
- статистика рекламных расходов.

## Выводы

LTV показывает равномерную тенденцию роста. На конец рассматриваемого периода затраты на привлечение покупателей из всех когорт окупились.

Показаны перспективные и неперспективные источники траффика и когорты. В среднем, окупаться вложения в маркетинг начинают на 5й месяц жизни когорты. С каждой новой когортой коэффициент удержания падает, как и количество новых посетителей. 

Длительность сессии показывает, что чаще всего пользователи уходят с сайта довольно быстро, не заинтересовавшись и не сделав покупку. Многие посетители (84%) покупок не совершают.
Количество отказов составляет 10%, рекомендовано проверить, нет ли технических ошибок и проанализировать качество UX-UI дизайна сайта.

## Инструменты и навыки 
*pandas*, *seaborn*, *Matplotlib*, *когортный анализ*, *юнит-экономика*, *продуктовые метрики*
