## These csv files were used for the completion of the project

### Data description

Three datasets were at my disposal.

The `visits_log.csv` file stores the server log with information about site visits, `orders_log.csv` - information about orders, and `costs.csv` - information about marketing expenses.

`visits_log.csv` **structure**

* `Uid` — unique user ID
* `Device` — user device category
* `Start Ts` — session start date and time
* `End Ts` — session end date and time
* `Source Id` — referal source ID

`orders_log.csv` **structure**

* `Uid` — unique user ID
* `Buy Ts` — order date and time
* `Revenue` — order amount

`costs.csv` **structure**

* `source_id` — advertising source ID
* `dt` — date of the advertising campaign
* `costs` — costs for this advertising campaign
