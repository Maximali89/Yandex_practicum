## Business performance analysis. Optimization of marketing costs for a service aggregator company

***Tech stack used: Python, Pandas, Matplotlib, Seaborn, cohort analysis, visualization of results, Retetion Rate, LTV, CAC, ROI.***

### Description of the project

For an aggregator of services in the field of mass entertainment, conduct analytics in order to optimize marketing costs

* Determine the use case of the product (website):
  *  duration of sessions
  *  conversion
  *  frequency of traversing from different sources
  *  number of visits
  *  repeated use
*  Identify a typical purchase scenario
*  Calculate the average bill and the number of purchases made over a period of time
*  Calculate the revenue for each customer
*  Determine the customer acquisition payback period for every marketing source

All the calculations were carried out including the use of cohort analysis.

### Data

Data from June 2017 to the end of May 2018 in three catergories

* website visits database (list of all the users' sessions)
* database of purchases on the website
* data on marketing costs (ayment for advertising)

### Analysis results

#### Product metrics

Daily, weekly, monthly active users

* DAU = 907
* WAU = 5621
* MAU = 23228

**Retention Rate**: in the first month of the cohort's existence the retention rate falls to 5-10%.\
The average user visits the site no more than once a day.\
The most typical session is 1 minute long.

#### Sales metrics

The typical purchase time is 1 minute.\
The average customer makes 7 purchases in six months (a little more than 1 purchase per month).

* The average check for all periods fluctuates around 4.8-5 units
* The average check is noticeably higher during the New Year period. It decreases in January. Bursts in mid-June and September 2017, late February 2018 (before March 8).
* The most active users make 3-4 purchases a month on average, other loyal users make 1.5-2 purchases on average.

#### Revenue and income per user (LTV)

* The cumulative customer value of the first six cohorts grows steadily to 7-12 units.
* During the first 6 months of existence, 4 out of seven cohorts showed an increase in LTV above 7 units.

#### Costs by advertising source

* The company makes the largest investments in source 3, then 4 and 5, and there are practically no expenditures for sources 9 and 10.
* Poor support of sources 9 and 10 affects the numbers of clicks (they are few compared to the rest of the sources)
* Sources 6,7,8 are not funded at all, respectively, the transitions from these sources are the least.

#### The main influx of buyers to the website comes from sources 3,4,5

#### Cost of customer acquisition from each source

* The most expensive sources for attracting users are sources 2–5.
* Source 3 brings users and increases sales, the influx of buyers from source 2 is much lower.
* Source 4 works best of all - the inflow of orders in aggregate for the year is the highest of all other advertising sources.
* Money is wasted on sources 9 and 10 - the inflow of users from them is the lowest.

#### What is the return on investment? (ROMI (ROI))

* The average payback period for cohorts is 5-6 months.
* The investments pay off after 8-9 months of cohorts' existence

The average LTV in 6 months after the first purchase is 7.97 units\
The average customer acquisition cost (CAC) over 6 months after first purchase is 7.19 units

**Marketing costs can be recouped in 6 months if the average CAC does not exceed 7.19 units.**

### Conclusions and recommendations

**Cost optimization**

* redistribute costs to sources of attraction (abandon the ineffective ones, optimize costs for the effective ones)
* monitor spending levels based on ROMI targets for 6 months
