## Fifa-21 Data Cleaning and Manipulation 

Here is my first practice on Ms SQL. I joined a data cleaning platform, being vast with excel and power query, I decided to try my acquired SQL skill. The saying that *a work of art is an imitation of reality*, this was quite challenging, some of the SQL functions are new to me, I learned from different channel and people to get this result achieved. This data cleaning has built my interest in learning more on SQL. 

I have attached my Query documentation, for everyone perusal.

## Introduction

This dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring).

The data-table consists of 18979 rows and 77 columns and some inconsistency in some columns such as;

- Contract column (incorrect delimiter (~)
- Height column (some rows are represented in cm while others are in feet and inches).
- Weight column (some rows are represented in kg while others are in lbs).
- Loan date end column has more null values than the supposed dates, according to column name.
- Value, Wage and Release columns have independent letters such M and K in abbreviation of million and also the Euro character, indicating the currency.
- W_F, SM and IR columns have special character ‘★’.
- The Hits column has the K independent letter  in abbreviation of thousand and also contain null values.
- Some club columns also have unwanted characters such as ‘.’ and ‘1’.


Objective

The main objective is to properly clean and manipulate where necessary. For all the inconsistency listed above was thoroughly cleaned,removed some columns and new columns such as end_year, start_year, Loan_status and Contract_status was also created.Also ensuring no duplicate. 

### Here is what the uncleaned data looks like when imported to MS SQL.

![](Uncleaned%20(1).png)
![](Uncleaned%20(2).png)
![](Uncleaned%20(3).png)
![](Uncleaned%20(4).png)

### And Here is the snippet from the cleaned data

![](Cleaned%20Data%20(1).png)
![](Cleaned%20Data%20(2).png)
![](Cleaned%20Data%20(3).png)
![](Cleaned%20Data%20(4).png)

### Kindly check [here](Fifa21-Dataset.pdf) for the SQl Query Procedures/ taken during the cleaning.
# Thank you!
