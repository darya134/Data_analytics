# 10. An analysis of user behavior in a mobile application

## Status
Complete

## Task

In this project, I analyzed the sales funnel and the results of an A/A/B test. I needed to understand how food startup users behave in a mobile application. It was agreed to make a decision based on the results of an A/A/B test after the designers wanted to change fonts throughout the application. To determine which font is the most effective, users were divided into three groups: two control groups with old fonts, and one experimental group with new fonts. Two control groups have certain advantages. If the two control groups are equal, the test can be assumed to be accurate. In the case where the two control groups differ significantly, the causes of the distortion can be identified.

After exploring the funnel of sales:
- The most frequent event was MainScreenAppear;
- MainScreenAppear was the most common event for users;
- Events occur in the following order: MainScreenAppear > OffersScreenAppear > CartScreenAppear > PaymentScreenSuccessful;
- Proportion of users progressed to the next step:
- For a sequence of events MainScreenAppear → OffersScreenAppear, 62% progressed to the next step of the funnel;
- For a sequence of events OffersScreenAppear → CartScreenAppear, 81% progressed to the next step of the funnel;
- For a sequence of events CartScreenAppear → PaymentScreenSuccessful, 95% progressed to the next step of the funnel.
- MainScreenAppear to OffersScreenAppear results in the most user loss;
47.70% of users made it from the first event to payment.

After exploring the results of an A/A/B experiment:
- In A/A experiment tested two control groups 246 and 247:
    - At a given critical level of statistical significance, the proportion of unique visitors who visited the funnel stage do not have statistically significant differences;
    - The groups were correctly split because there was no statistical significance.

- In A/B experiment tested two control groups 246 and 247 with experimental group 248:
    - At a given critical level of statistical significance, the proportion of unique visitors who visited the funnel stage do not have statistically significant differences;
    - Changing the fonts did not affect the behavior of users. That is, changing the fonts will not affect sales.


## Python libraries

*pandas*, *matplotlib*, *seaborn*, *plotly*, *numpy*, *scipy*, *math*
