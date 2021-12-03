## Determination of a profitable mobile plan for a telecom company pased on customer data

*Tech stack used: Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, descriptive statistics, statistical hypothesis testing*

### Description of the project

There was a need for a preliminary analysis of mobile plans for a small sample of customers in order to adjust the advertising budget. The task was to find out which of the two mobile plans is more commercially viable. Data on 500 users.

### Data preprocessing

* Data types conversion
* Detection and correction of data errors.
* Handling of missing values.
* Analysis of the key parameters for every user:
  * calls made and talk time minutes used
  * text messages sent
  * internet data used
  * monthly revenue from each user

### Analysis of data
* Customer behaviour description (talk time minutes used, text messages send, mobile data used, other costs for communication services)
* Culculation of statistical values (mean, variance, standard deviation)
* Histograms plotting and distribuition descritpion

### Testing of hypotheses
Testing of hypotheses about the equality of average revenue for different mobile plans and regions.
* Formulation of the null and alternative hypothesis
* Determination of the criteria for hypothesis testing

### Analysis results
* Most ofthe revenue is brought by the more popular and cheap mobile plan due to additional services charged.
* Customers using the "expensive" plan hardly ever use additional services.
* Analysis of the proposed hypotheses
  1. The hypothesis was confirmed: "The average revenue from users of both plans differ"
  2. The hypothesis was not confirmed: "The average revenue of users from Moscow differs from the revenue of users from other regions."
