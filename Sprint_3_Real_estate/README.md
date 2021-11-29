## A study of apartment sales advertisements in St. Petersburg area

*Tech stack used: Python, Pandas, Matplotlib.*

### Description of the project

Parameter definition for an automated tracking system for anomalies and fraudulent schemes in real estate ads. The data source is the apartments sales adds in St. Petersburg and the surrounding region during a period of several years.
There are two types of data available for each advertiseent:
* custom data
* automatically generated data and cartographic database

### Data preprocessing

* Determination and filling of missing values (description, determination of possible reasons for the appearance, development of a scheme for filling in gaps).
* Data types replacement
* Auxiliary data calculation (price per sq m, living space to total area ratio, etc.)
* Categorization by total number of floor in the advertisements

### Exploratory analysis

* Apartments' parameters research:
  * Total area, price, number of rooms, ceiling height
  * Histogram plotting for each parameter
  * Determination of outliers and confidence intervals
* Studying the sale time of an apartment:
  * Analysis of the ad posting period
  * Histograms plotting
  * Calculation of statistical parameters
* Analysis of the factors determining the cost of an apartment:
  * Total area, number of rooms, distance from the city center
  * Number of floors (first floor, last floor or other)
  * Posting date: day of the week, month or year
* Analysis of the geographic characteristics of the ads:
  * TOP -10 populated areas with the largest number of ads (average price per sq m, MAX and MIN prices)
  * Determination of the boundaries of the " city center" for St. Petersburg, based on the average price per sq m
  * Comparison of data analysis (by key parameters) for apartments inside the city center and apartments for the city as a whole

### Analysis results

* The bulk of apartments advertised have an area ranging 30-100 sq m
* A quick sale can be considered as a period of 3 days
* Dependence levels of the apartment price on various factors have been identified
* TOP 10 populated areas include: St. Petersburg, Murino village, Shushary village, Vsevolozhsk, Pushkin, Kolpino, Pargolovo village, Gatchina, Kudrovo village, Vyborg
* Most ads were posted in St. Petersburg
* The radius of advertisements from within the city center limits was 8 km.

**The average apartment for sale in the center of St. Petersburg has the following characteristics: it is a 2-room apartment with an area of 60 sq m with ceilings height of 2.75 m, sold in 3 months (95 days) at a price of 6.9 million rubles.**
