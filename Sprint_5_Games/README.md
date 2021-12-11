## A study of the video games market based on 30-years sales data and users and expert assessments

*Tech stack used: **Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, Exploratory Data Analysis (EDA), Data Preprocessing, descriptive statistics, statistical hypothesis testing.***

### Description of the project

Based on open data on the sales of computer games over the past 30 years, an analysis of the patterns that determine the commercial success of a game was needed. The analysis is carried out for an online store in order to determine a potentially successful product and plan a marketing campaign. The data contains information on game sales by different regions of the world and ratings of specialists and users.

### Data preprocessing
* Data presentation normalization
* Data types conversion
* Handling of missing values
* Calculation of total sales for all regions

### Exploratory data analysis
* Determination of the suitable research period
  * Game sales by year
  * Analysis of the "lifetime" of gaming platforms
* Identifying top-selling gaming platforms
* Statistical analysis of global game sales by platform
  * Impact of critics' and users' reviews on sales (building scatterplots, calculating correlations)
* Determination of TOP selling genres
* Based on users by regions
  * Determination of TOP-5 popular platforms (differences in sales shares)
  * Determination of TOP-5 popular genres (differences in sales shares)
* The impact of ratings on sales in a particular region

### Testing of hypotheses

Testing of hypotheses about the equality of average user ratings for different gaming platforms and genres.

* Formulation of the null and alternative hypothesis
* Determination of the criteria for hypothesis testing

### Analysis results

* TOP-6 platforms by sales for the entire period - PS2, X360, PS3, Wii, DS, PS.
* The typical "lifespan" of more or less successful platforms is 10 years (+/- 2 years)
* The suitable research period is 2007-2016
* Global sales of TOP-10 platforms are falling during the period 2007-2016
* There is an influence of reviews from critics and users on sales.
* Top selling games genre is Action games
* Most popular platforms (Top 5) - X360 - Wii - PS3 - DS - PS4
* Most popular genres (Top 5) - Action - Shooter - Sports - Misc - Role-Playing / Racing
* The impact of the ESRB rating on sales is almost zero.
* Analysis of the proposed hypotheses
  1. The hypothesis was not confirmed: "The average user ratings for the Xbox One and PC platforms are the same"
  2. The hypothesis was confirmed: "The average user ratings for the Action and Sports genres are different" 
