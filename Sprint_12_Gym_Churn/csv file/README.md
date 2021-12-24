## This csv file was used for the completion of the project

### Data description

`gym_churn.csv` **structure**

The data contains data for the month before the churn and the fact of churn for a specific month. The dataset contains the following fields:

* `Churn` — whether the client left during the current month
* Current fields in the dataset:
  * Client data for the previous month before checking the churn status:
    * `gender` — client's gender
    * `Near_Location` — living or working in the area where the fitness center is located
    * `Partner` — an employee of the gym or partner company (cooperation with companies whose employees can receive subscription discounts - in this case, the fitness center stores information about the client's employer)
    * `Promo_friends` — membership bought as part of the "bring a friend" campaign (used a refferal promo code when paying for the first subscription)
    * `Phone` — provided phone number
    * `Age` — client's age
    * `Lifetime` — time from the moment of the first visit to the fitness center (in months)
* Information based on the history of visits, purchases and information about the current status of the client's subscription:
  * `Contract_period` — duration of the current valid subscription (month, 3 months, 6 months, 12 months)
  * `Month_to_end_contract` — time left until the end of the current active subscription (in months)
  * `Group_visits` — group classes attended
  * `Avg_class_frequency_total` — average frequency of visits per week for the entire time since the start of the subscription
  * `Avg_class_frequency_current_month` — average frequency of visits per week for the previous month
  * `Avg_additional_charges_total` — total revenue from other services of the fitness center: cafe, sports goods, beauty and massage parlor
