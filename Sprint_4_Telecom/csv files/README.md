## These csv files were used for the completion of the project

### Data description

* **`users.csv` table (information about users):**
  * `user_id` -  user's unique ID
  * `first_name` - user's given name
  * `last_name` - user's family name
  * `age` - user's age (in years)
  * `reg_date` - plan activation date (day, month, year)
  * `churn_date` - plan termination date (if the value is missing, then the plan was still active at the moment of data upload)
  * `city` - user's city of residence
  * `tarif` - tariff plan name

* **`cals.csv` table (information about calls):**
  * `id` - unique call number
  * `call_date` - call date
  * `duration` - call duration in minutes
  * `user_id` - caller's ID

* **`messages.csv` table (information about text messages):**
  * `id` - unique text message number
  * `message_date` - text message date
  * `user_id` - sender's ID

* **`internet.csv` table (information about internet-sessions):**
  * `id` - unique session number
  * `mb_used` - mobile data used during the session (in megabytes)
  * `session_date` - internet-session date
  * `user_id` - user's ID

* **`tariffs.csv` table (information about the mobile plans):**
  * `tariff_name` - mobile plan name
  * `rub_monthly_fee` - monthly subscription fee in russian rubles
  * `minutes_included` - minutes of talk time included in the monthly fee
  * `messages_included` - text messages included in the monthly fee
  * `mb_per_month_included` - mobile data included in the monthly fee (in megabytes)
  * `rub_per_minute` - cost of a minute of conversation exceeding the plan's limit (for example, if the mobile plan includes 100 minutes of conversation per month, then a fee will be charged from 101 minutes)
  * `rub_per_message` - cost of a text message exceeding the plan's limit
  * `rub_per_gb` - cost of additional GB of mobile data exceeding plan's limit (1 GB = 1024 MB)
