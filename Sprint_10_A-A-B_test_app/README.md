## Analysis of user behavior in a mobile application. Evaluation of the results of the A/A/B test on changing the fonts in the application.

*Tech stack used: Python, Pandas, Matplotlib, Seaborn, Plotly, A/B testing, Statistical Hypotheses Testing, Product Metrics, Event Analytics*

### Description of the project

The task of the project was to understand the behaviour of a mobile application users. It was required to explore the sales funnel, understand how the user's steps that lead to a purchase. It was also necessary to figure out how many users make it to the purchase, and how many get stuck at previous steps and which steps they are.

### Analysis results

**Carrying out the test**

* The test was held from July 25 to August 7, 2019.
* Five key events of interaction with the system were monitored - "Home Screen", "Payment", "Cart", "Offer", "Tutorial".
* 7551 users registered in total.
* On average, there are 32 events per user.
* Full data were received from August 1, 2019 until the end of the day on August 7, 2019.
* The post-filtering loss was 1.16% of the records.
* For the period from August 1 to August 7, users from group B are more active than from groups A1 and A2.

### Event funnel analysis

Typical Event Funnel:

1. `MainScreenAppear`- Main Screen
2. `OffersScreenAppear` - Offer
3. `CartScreenAppear` - Cart
4. `PaymentScreenSuccessful` - Payment

The `Tutorial` event was excluded from the funnel in question due to the low user activity on this parameter, at the same time as this action is clearly optional in the general scenario of using the application.

**The application script allows for non-linearity, without prejudice to achieving the ultimate goal of "payment".**

* **Conversion** 
  * In a simple funnel, the conversion is 48% (% of all users who made a payment).

### Analysis of test results

* **The groups for the test are prepared correctly, differences are acceptable:**
  
  * The difference in groups is 1-2% in terms of the number of users
  * Users of different groups do not overlap
  * The control groups of the A/A test were tested for correctness by assessing the difference in terms of the key metric "Conversion". There is no statistically significant difference.
  * The control groups of the A / A experiment were tested for differences in the proportion of users who performed an action to the total number of users. There is no statistically significant difference.

* **Test results:**
  
  * The control groups and group B were compared in terms of the proportion of users who performed an action to the total number of users. There is no statistically significant difference.

**The experiment to change the font did not make any noticeable difference in the user behavior.**
