# Customer-Segmentation
This project aims to understand customer responses to different promotional offers sent by Starbucks and to come up with better approaches to send specific promotional deals to customers. The goal is to segment customers and decide how to relate to customers in each segment to maximize the value of each customer to the business. The project also aims to answer the following business questions:

How are the offers determined according to specific customer groups?
How can the approaches of offers be enhanced?
The dataset used in this project is provided by Starbucks Company and contains three CSV files:

portfolio.csv: data about offers sent to customers (10 offers x 6 columns)
profile.csv: demographic data of customers (17,000 customers x 5 columns)
transcript.csv: customer response to offers and transactions made (306,648 events x 4 columns)
Data Preparation
Data cleaning is applied for all three files. Missing values are checked and data types are verified. For data transformation, new columns are created and some columns are prepared for suitable format.

# Exploratory Data Analysis
Customer behavior features are extracted by creating a new table using the transcript table. The number of received offers, viewed offers, completed offers, transactions, and spending money are calculated for each customer.

# Modelling
Firstly, the K-Means clustering algorithm is used to determine customer groups. After that, CatBoostClassifier and Random Forest algorithms are applied and compared. The Pycaret library is used for clustering and classifications.

# Conclusion
Customers are grouped according to their behaviors, and it is important to analyze customers. The company enhances offers according to customer group behaviors, and they can make predictions related to customer age, income, and gender. We can see the distribution of customer properties according to behavior groups.
