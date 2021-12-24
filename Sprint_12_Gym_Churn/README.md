## Fitness Center Customer Churn Indicators

*Tech stack used: Python, Pandas, Matplotlib, Seaborn, Plotly, Sklearn, SciPy*

### Tasks of the project

* Learn how to predict the likelihood of a churn (at the next month's level) for each client
* Form typical clients' profiles: highlight several of the most striking groups and characterize their main properties
* Analyze the main features that most strongly influence the churn rate
* Formulate the main conclusions and develop recommendations for improving the quality of work with clients:
    1. identify the target groups of clients
    2. propose measures to reduce the churn rate
    3. identify other features of customer interactions

### Analysis results

**Distribution of signs for those who left (churn) and those who stayed**

* Younger people leave more often than older ones
* Customers who leave are spend less
* Customers in churn generally buy a one month membership
* Only newcommers leave, if a client has been in the gym for more than 5 months, then the propability of them leaving is almost zero
* Customers who leave, most often visit the gym once or twice a week
* If a client has not visited the gym in a month, then most likely they will not return again, but if they visited the hall more than 4 times, then most likely they will become a regular customer.

### Proposals

* The first step is to pay more attention to new customers, since this is the most influential sign of churn.
* And also pay attention to the fact that new customers' spending at the peak is higher than all other clusters, which is why for them it is necessary to create promotions and additional discounts for the first time in order to keep them.
* New customer often buy a subscription for one month, most likely to scout out the situation, this is where you need to interest them, perhaps you need to offer only a subscription for 3 months to new customers + the opportunity to attend a paid lesson for free, so they can get acquainted with already regular customers, which is very important.
* Other than that, regular customers have a hyper minimal propensity to churn, but they also tend to buy a subscription for one month, it would be worth creating a loyalty program, thus reducing the likelihood of a churn of regular customers
