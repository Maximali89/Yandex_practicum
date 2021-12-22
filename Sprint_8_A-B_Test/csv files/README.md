## These csv files were used for the completion of the project

### Data description

**Data for the first part of the project**

`hypothesis.csv` **structure**

* `Hypothesis` — a short description of the hypothesis
* `Reach` — user reach on a 10-point scale
* `Impact` — impact on users on a 10-point scale
* `Confidence` — confidence in the hypothesis on a 10-point scale
* `Efforts` — resource consumption for hypothesis testing on a 10-point scale. The higher the Efforts value, the more expensive is the hypothesis testing.

**Data for the second part of the project**

`orders.csv` **structure**

* `transactionId` — order ID
* `visitorId` — ID of the user who made the order
* `date` — date of the order placement
* `revenue` — order's revenue
* `group` — the A / B test group that the order fell into

`visitors.csv` **structure**

* `date` — date
* `group`— A/B test group
* `visitors`— the number of users on the specified date in the specified A/B test group
