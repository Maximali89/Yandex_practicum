## Data-Driven Decision Making. Hypothesis prioritization, A/B test

*Tech stack used: Python, Pandas, Matplotlib, Seaborn, Hypothesis prioritization (ICE, RICE), A/B test (Mann-Whitney-Wilcoxon Test)*

### Description of the project

Together with the marketing department of the online store, a list of hypotheses to boost revenue was prepared. It is required to prioritize the hypotheses, run an A/B test and analyze the results.

### Data

* A list of 9 hypotheses, with data for each prioritization parameter.
* For the A/B test:
  * data on orders in the two groups
  * data on visits in the two groups

### Analysis results

**Hypothesis prioritization**

* Prioritization calculations were performed using two methods ICE and RICE
  * ICE hypothesis rating (TOP-5): 8, 0, 7, 6, 2 (descending order)
  * RICE hypothesis rating (TOP-5): 7, 2, 0, 6, 8 (descending order)
* The priority ranking changed after the introduction of one factor, audience reach. Maximum audience reach is the priority according to all hypotheses.

List of relevant hypotheses for testing (descending order of priority)

1. Add a subscription form to all main pages to build a customer base for email newsletters.
2. Add product recommendation blocks to the website of the online store to increase conversion and average order value.
3. Add two new channels to attract traffic, which will attract 30% more users.
4. Display banners with up-to-date promotions and sales on the main page to increase conversion.

**A/B test analysis

* The revenue for both groups grew steadily throughout the test.
* The average bill of group B is growing steadily.
* The conversion in group B is 10% higher than in group A.
* Fluctuations in conversions by the end of the test remain within 2-3%.

Boundary for identifying abnormal users

* Upper boundary for number of orders according to the 95th percentile: 2
* Upper boundary for total amount spent per user according to the 95th percentile: 27570 units
* Percentage of data discarded for cleaning: 7.12%
* Number of abnormal users: 73

**Conclusions from raw data**

* There are statistically significant differences in the conversion of groups A and B.
* The conversion of group B is 15.2% higher (on average) than in group A.
* There are no statistically significant differences in the average bill of groups A and B.
* The average bill in group B is 24.2% higher (on average) than in group A.

**Conclusions from filtered data**

* There are statistically significant differences in the conversion of groups A and B. The result has not changed.
* The conversion of group B is 16.8% higher (on average) than in group A. The indicator increased by 1.6%.
* There are no statistically significant differences in the average bill of groups A and B. The result has not changed.
* The average bill in group B is 3.5% lower (on average) than in group A. The indicator decreased by 27.8%.

After excluding the abnormally expensive purchases from the analysis, it turned out that the difference in the average bill between the groups isn't really significant (on average).

**Decision based on test results**

1. Stop the test
2. Register the presence of statistically significant differences in conversion between groups based on raw data and after filtering the abnormal data.
3. 
