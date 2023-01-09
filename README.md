# travel_agency

В тревел-агентстве планируется маркетинговая акция, направленная на вовлечение пользователей, увеличение активности юзеров из Германии и Австрии. Хочется не только 
нарастить базу активных пользователей, но и увеличить количество покупок, которые приходятся на одного пользователя. Акция будет действовать в апреле 2022 года.

**Суть акции:**

- Каждый пользователь получает гарантированный приз - баллы лояльности - при достижении 10 покупок в месяц стоимостью больше 3000 рублей
- Случайный участник акции получит главный приз - билеты в Дубай стоимостью в 50000

Маркетинг просит посчитать число пользователей, которых мы сможем потенциально охватить этой акцией, а также смоделировать пессимистичные варианты развития событий:

- Какое максимальное число баллов лояльности мы можем дать пользователям на этих рынках при описанных условиях гарантированного приза, оставаясь при этом в рамках 
прибыльности?
- Какие максимальные потери мы понесём при таких условиях акции?
- Сколько пользователей следует привлечь, чтобы покрыть все расходы на акцию и получить прибыль?

Также маркетинг просит сделать дешборд, в котором можно было бы наблюдать за ходом акции в режиме реального времени, чтобы понимать, соответствует ли наша модель 
реальности.

> **Описание метрик компании с формулами:**
> 
> - Operating Profit = Revenue - Costs
>     - Revenue = Users (?) * Purchases per user (10) * Average Transaction Value (3000) * Margin (Base)
>         - Margin = Commission (Base) / Transaction Value (Base)
>     - Costs = Fixed costs (Base) + Marketing costs
>         - Marketing costs = Loyalty costs (?) + Promo costs (50000)
> 
> ***Примечание:** знак (?) рядом с метрикой означает, что её необходимо рассчитать.*
> 
> Следует опираться на усреднённые данные по всем рынкам.*

Финальный файл marketing_study.xlsx содержит основные исследования и выводы, на основании которых можно привлечь больше клиентов. 
