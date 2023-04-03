# Customer-Segmentation
 The goal of segmenting customers is to decide how to relate to customers in each segment in order to maximize the value of each customer to the business. The purpose is to understand customer response to different offers in order to come up with better approaches to sending customers specific promotional deals. 

The purpose of this project is to understand customer response to different offers in order to come up with better approaches to sending customers specific promotional deals. The dataset used in this project is provided by Starbucks Company and contains three CSV files: portfolio.csv, profile.csv, and transcript.csv.

The portfolio.csv file contains data about offers sent to customers, including 10 offers with 6 columns. The profile.csv file contains demographic data of 17,000 customers with 5 columns. The transcript.csv file contains customer response to offers and transactions made, with 306,648 events and 4 columns.

# Project Structure
customer_segmentation.py: The main Python script that performs customer segmentation using K-Means clustering algorithm and CatBoostClassifier and Random Forest algorithms for classification.
portfolio.csv: The input CSV file containing data about offers sent to customers.
profile.csv: The input CSV file containing demographic data of customers.
transcript.csv: The input CSV file containing customer response to offers and transactions made.
customer_segments.csv: The output CSV file containing customer segments.
README.md: This file.
