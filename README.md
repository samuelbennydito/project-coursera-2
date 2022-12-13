# Background

Scenario: Your data analyst team exported the Google Analytics logs for an ecommerce website into BigQuery and created a new table of all the raw ecommerce visitor session data for you to explore.

Objectives
1. Use BigQuery to find public datasets
2. Query and explore the ecommerce dataset
3. Create a training and evaluation dataset to be used for batch prediction
4. Create a classification (logistic regression) model in BQML
5. Evaluate the performance of your machine learning model
6. Predict and rank the probability that a visitor will make a purchase

Results
1. Of the top 6% of first-time visitors (sorted in decreasing order of predicted probability), more than 6% make a purchase in a later visit.
2. These users represent nearly 50% of all first-time visitors who make a purchase in a later visit.
3. Overall, only 0.7% of first-time visitors make a purchase in a later visit.
4. Targeting the top 6% of first-time increases marketing ROI by 9x vs targeting them all!
