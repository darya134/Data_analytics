# 04. An analysis of a mobile service provider's tariffs

## Task

A mobile service provider offers two tariff plans. The commercial department needs to understand which tariff brings in more money to adjust the advertising budget. In this project I analyzed the behavior of 500 users and decided which tariff is better.

Users of smart tariff use the operator's services more than users of ultra tariff. Smart tariff has a greater variance and standard deviation, except for the number of messages parameter.

All histograms are positively skewed. Due to the greater dispersion, ultra has longer tails than smart.

Number of calls: smart has a main peak of 25, ultra - about 14.
Minutes usage: smart has two peaks - 80 and 90 minutes, ultra - about 120. Moreover, smart and ultra have small peaks at near-zero values. In general, smart tariff customers talk no more than 600 minutes a year, whereas ultra customers talk almost 900 minutes.
Messages usage: in both tariffs, many people use messages very little. This is the result of earlier replacing 85 missing values with zeros, which we observed earlier. In general, smart tariff customers send no more than 80 messages, whereas ultra customers send around 100 messages.
Internet traffic usage: both tariffs have an upper limit of 20-25 gb, after which there are few values. In smart, the peak is around 9 gb; in ultra, there are two peaks, one about 3 gb and the other about 4 gb.
Monthly spendings are mostly below the tariff plan fee, which is 550 for smart and 1950 for ultra. While some users of the smart tariff overspend their tariff limits and spend 3,000 a month. There are very few ultra tariff customers who exceed their monthly tariff limits and spend more than 2,700 a month.

After testing the hypotheses, it became clear that:

The average user revenue for the "Ultra" and "Smart" tariffs is statistically different;
Moscow's average user revenue is statistically equal to that of other regions.
It can be concluded that ultra tariff users spend more minutes on calls. On the other hand, smart tariff users use more internet traffic and often overspend their tariff limits which brings more profit to the business.

## Python libraries

*pandas*, *matplotlib*, *numpy*, *seaborn*, *scipy*
