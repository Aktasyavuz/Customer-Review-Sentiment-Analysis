# Customer-Review-Sentiment-Analysis
Customer Review Sentiment Analysis Pipeline Demo for Amazon Fine Food Reviews.
The dataset is available in: URL: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

The dataset includes:

Reviews from October 1999 - October 2012

more than 500,000 reviews

more than 250,000 users

more than 74,000 products

The columns are following:

Id: Row Id
ProductId: Unique identifier for the product
UserId: Unique identifier for the user.
ProfileName: Profile name of the user. -HelpfulnessNumerator: Number of users who found the review helpful
HelpfulnessDenominator: Number of users who indicated whether they found the review helpful or not
Score: Rating between 1 and 5
Time: Timestamp for the review
Summary: Brief summary of the review
Text: Text of the review
A random sample of 10.000 reviews from the full set have been used to ensure a fast and efficient training and to keep the analysis manageable.

This notebook demonstrates an NLP Pipeline for classifying reviews into positive, negative, or neutral (If neutral, will be dropped from the dataset). The Notebook includes:

Business Problem
High-level NLP system design / Overview
Data aquisition
Exploratory Data Analysis (EDA)
Text Cleaning
Pre-processing
Feature Engineering
Modeling
Evaluation
Final Discussion
BUSINESS PROBLEM
Companies depend on customer feedback to understand product performance and customer satisfaction nowadays.

Even though Amazon reviews provide a massive and unstractured text data, it is impossible to analyze it manually at this scale.

The company`s current inability to automatically identify customer review sentiment leads the company to detact the issues related to the products late, miss the customers insights, and uneffective product improvements.

Solving this problem will provide several important benefits to the company:

Early detection of product issues
Improved customer Satisfaction
Better decicision making for product development
Effective marketing and sales strategies
Reduced manual workload
Take action faster than the competitors.
The problem can be formulated as a "text classification" task in NLP. The goal is to assign a sentiment label (IF POSITIVE = 1, IF NEGATIVE = 0) to each customer review based on the review`s textual content automatically.

Each review will be treated as an input, and the system will predict whether the sentiment expressed in the review is positive or negative.
