## Data analysis and preparation for presentation. Moscow catering market.

*Tech stack used: Python, Pandas, Matplotlib, Seaborn, RegEx, external data access.*

### Description of the project

The task of this project is to conduct a market a market research for the catering industry in Moscow in order to determine which type of restaurant would be successful. The project's plan is to use robot waiters instead of traditional human waiters.

### Analysis results

The composition of the database of catering establishments:

* Most common type is "Café" - 6068 establishments
* The next three types - "Canteen" (2584), "Restaurant" (2281), "Fast food" (1897)
* Least common types are - "Cafeteria" (395), "Diner" (348), "Shop (culinary department)" (273)

**Mostly, chain enterprises are cafes, restaurants, fast food establishments.**

**Typical number of seats for TOP-3 types of chain enterprises:**

* For cafés, the most typical number of seats is 20-50.
* Most of the "fast food enterpriseы" do not have their own seats, since this is not stipulated by the format of the establishment, or they are located in a shopping center, etc.
* For restaurants, the most typical number of seats is 50-90.

**Average number of seats in catering facilities - TOP-3**

1. Canteen - 100 seats
2. Restaurant - 80 seats
3. Bar/Buffet/Café - 30-35 seats (approximately same average number of seats)

**TOP-10 streets in Moscow in terms of the number of catering establishments:**

1. Mira Avenue
2. Profsoyuznaya Street
3. Leningradský Avenue
4. Presnenskaya Naberezhnaya
5. Varshavskoye Highway
6. Leninskiy Avenue
7. Vernadskogo Avenue
8. Kutuzovsky Avenue
9. Kashirskoe Highway
10. Khodynsky Boulevard

**Streets with one establishment**

There are 768 such streets in total. To determine the districts and districts of Moscow for each street, I used the MosGaz website (https://noosphere.ru/pubs/714051)

There are three main groups by the number of streets with one enterprise:

* Most streets with one establishment in the Central Administrative District - 186
* Four districts with 55-70 streets - Eastern Administrative District (71), North-Eastern Administrative District (65), Northern Administrative District (55), South-Eastern Administrative District (55) - the eastern part of the map of Moscow from North to South
* Four districts with 30-40 streets - Western Administrative District (41), Southern Administrative District (30), North-Western Administrative District (28), South-Western Administrative District (28) - the western part of the map from North to South.

**The typical number of seats on the streets from the TOP-10 list by the number of establishments**

The number of seats depends on the area of the city.

* The general trend is the number of seats between 0 and 50
* If we exclude locations in shopping centers, food courts, food markets, then most enterprises have 10-50 seats.
* The number of seats depends on the number of large shopping centers in the region (district) where the уыефидшырьуте is located.

**Project development recommendations**

* The "Café" format is the most suitable for the project idea
* Location - Central or Eastern districts of Moscow
* Streets with a small number of catering establishments (1+)
* Seating capacity - 20-40
* Chain "Café" business model

**Pros:**

1. **Smaller competition:**

    * The central area has the most streets with one establishment. Further on the list are the Eastern districts of Moscow.
    * There are generally fewer establishments in the Eastern districts than in other districts.

2. **Facility type and number of seats:**

    * A cafe, as a separate facility, assumes its own limited area. Positioning it in shopping centers or food courts will make it difficult to organize it from a technical point of view - there is no "own" territory for working with guests, and therefore there is no need for waiters.
    * The number of seats 20-50 is optimal for constant traffic, and therefore the work of waiters. If there are 0-20 seats, then the establishment is supposed to work with the flow of guests taking the food "take away".

3. **Chain business model brings more profit due to unrealized procurement and scalability of business solutions**

**Cons:**

1. **Cost:**

    * A separate space is an expensive solution, especially in the Central District
    * Chain business model requires a large initial investment

2. **Restrictions on the number of places:**

    * Number of seats 0-10 - the option of working at food courts in a shopping center, etc. a cheaper option for launching a project. But it carries material risks, and it is in such an "unlimited" territory that one cannot be confident in the anti-vandal properties of the robot. In any case, not at the initial stage of project development. Until the system of working in a confined space has been worked out, the risks are great.

3. **Location:**

    * A careful analysis of the location (by streets and districts) is required, perhaps there are some hidden reasons for low activity on the streets with one business
    * High competition on busier streets will require a longer ROI
