## A study of the reliability of borrowers based on statistics on the solvency of the bank's clients.
***Tech stack used: Python, Pandas.***

### Description of the project

To build a credit scoring model (a system that assesses the ability of a potential borrower to repay a loan to a bank), it is required to determine whether the marital status and the number of children affect the clients' timely loan repayment. The analysis for the credit department is based on the statistical data regarding the solvency of clients

### Data preprocessing

* Determination and filling of missing values (description, determination of possible reasons for the appearance, development of a scheme for filling in gaps).
* Data types replacement (defining replacement types and a method for changing data types).
* Detection and removal of duplicates (methods of search and removal, identification of the reasons of their appearing)
* Categorization of the data using lemmatization in the **"loan purposes"** column values.
* Categorization of other data (designation of "dictionaries" of categories)

### Analysis of the dependence of the loan repayment time on the following factors:
* Number of children
* Marital status
* Income level
* Purposes of the loan

### General conclusion

The dependence of loan repayment on the presence of children, marital status, income level, loan purpose is minimal and fluctuates within 2% of the total volume of debts 8.8%
There is a slightly larger dependence on the marital status, where **unmarried** clients have a 10% risk of not repaying the loan in time, whereas **widowed** clients' risk is only 6.5%
