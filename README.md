# Background

Scenario: Your data analyst team exported the Google Analytics logs for an ecommerce website into BigQuery and created a new table of all the raw ecommerce visitor session data for you to explore.

Objectives
1. In this lab, you learn to perform the following tasks:
2. Use BigQuery to find public datasets
3. Query and explore the ecommerce dataset
4. Create a training and evaluation dataset to be used for batch prediction
5. Create a classification (logistic regression) model in BQML
6. Evaluate the performance of your machine learning model
7. Predict and rank the probability that a visitor will make a purchase

Results
1. Of the top 6% of first-time visitors (sorted in decreasing order of predicted probability), more than 6% make a purchase in a later visit.
2. These users represent nearly 50% of all first-time visitors who make a purchase in a later visit.
3. Overall, only 0.7% of first-time visitors make a purchase in a later visit.
4. Targeting the top 6% of first-time increases marketing ROI by 9x vs targeting them all!
