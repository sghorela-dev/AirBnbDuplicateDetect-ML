# AirBnbDuplicateDetect-ML  -  Project Overview 
## Scam Rental Detection on Airbnb

This project aims to detect scam rental postings on Airbnb. Scam rental postings refer to listings that are fraudulent and do not exist, or the listing does not match what is advertised. To accomplish this, we will use machine learning techniques and analyze the data to identify patterns and characteristics of scam postings and fake reviews.

## Data Collection

The data was collected from two sources:

-   `listings.csv`: contains information about the rental listings such as the name, description, location, price, and number of reviews.
    
-   `review_data.csv`: contains reviews made by customers about the rental listings such as the comments, date, and reviewer name.
    

## Data Preprocessing

The collected data was preprocessed by removing missing values, converting data types, and dropping unnecessary columns. We also performed feature engineering by creating new variables such as the number of listings associated with a single account, the similarity of reviews from different accounts, and the difference in the minimum and maximum nights allowed.

## Exploratory Data Analysis

We analyzed the data to gain insights into the features of the scam and non-scam rental postings. We compared the distributions of various features such as the price, number of reviews, and location. We also looked at the correlation between variables and how they affect the likelihood of a rental posting being a scam.

## Model Building

We trained a machine learning model to detect scam rental postings using the preprocessed data. We used a logistic regression model and achieved an accuracy of
