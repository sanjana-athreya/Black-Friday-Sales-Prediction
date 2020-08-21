# Black Friday Sales Prediction

The dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand our feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem. The dataset has 537,577 rows and 12 columns.

This project analyzes the Black Friday sales data and tries to answer these key business questions :

- What are maximum products sold?
- Which Product category has highest sales?
- Finding the buyer's age group and their product of interest.
- Finding the marital status of the buyers.
- Analyzing the gender group, which has high interest in the sales

This can be used to understand the customer purchase behaviour (specifically, purchase amount) against various features like Products of different Categories, Gender, Age, Occupation of Customer, etc.

This project also aims at creating a simple predicting model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

## Data Dictionary :
| Variable                     | Definition                                |
| :----------------------------| :-----------------------------------------| 
| User_ID                      | User ID                                   | 
| Product_ID                   | Product ID                                |
| Gender                       | Sex of the User                           |
| Age                          | Age of the User(in bins)                  |
| Occupation                   | Occupation of the User (Masked)           |
| City_Category                | Category of City(A,B,C)                   |
| Stay_In_Current_City_Years   | Number of years of stay in Current City   |
| Marital_Status               | Marital Status of the User                |
| Product_Category_1           | Product Category 1(Masked)                |
| Product_Category_2           | Product Category 2(Masked)                |
| Product_Category_3           | Product Category 3(Masked)                |
| Purchase                     | Purchase Amount(Target Variable)          |
