# 04. An analysis of a mobile service provider's tariffs

## Status
Complete

## Task

A mobile service provider offers two tariff plans. The commercial department needs to understand which tariff brings in more money to adjust the advertising budget. In this project, I analyzed the behavior of 500 users and decided which tariff is better.

## Conclusion

Users of smart tariff use the operator's services more than users of ultra tariff. Smart tariff has a greater variance and standard deviation, except for the number of messages parameter.

Monthly spendings are mostly below the tariff plan fee, which is 550 for smart and 1950 for ultra. While some users of the smart tariff overspend their tariff limits and spend 3,000 a month. There are very few ultra tariff customers who exceed their monthly tariff limits and spend more than 2,700 a month.

After testing the hypotheses, it became clear that:

- The average user revenue for the "Ultra" and "Smart" tariffs is statistically different;
- Moscow's average user revenue is statistically equal to that of other regions.

It can be concluded that ultra tariff users spend more minutes on calls. On the other hand, smart tariff users use more internet traffic and often overspend their tariff limits which brings more profit to the business.

## Python libraries

*pandas*, *matplotlib*, *numpy*, *seaborn*, *scipy*
