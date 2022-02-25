# Data-Science-Capstone-project

# Project Theme: 
Theme Classification or Summarization for Customer Review Comment

# Problem: 
Receive many customer review from Amazon daily and need to understand the main idea or theme from long text comment

# Data Source & Data Gathered: 
  - Customer Comment from Amazon.com
  - Data gathered: Latest customer review comment data from 2017 to 2022 YTD

# Data processing:
Reviewed 2022 YTD data and already classified all customer comment to below 5 theme for model training data:
  - Product Design (Function/ Comfortability/ Material)
  - Durability
  - Assembly or Installation
  - Pricing/ Value of Money
  - Shipping/ Logistic/ Packaging

# Data Cleaning:
Using Pandas for below data cleaning task

  - Drop unnecessary columns
  - Remove Data with no comment
  - Remove Data with no label
  - Remove duplicate comment/ data as variant aproducts under same collection is sharing same comment
  - Remove duplicate comment/ data as data is capturing latest comment daily and it will repeat the same comment if no new comment in daily data
  - Remove blank comment and comment not related to above 5 themes from training data

# Basic Data Exploration
  - Basic Table to show Label distribution
  - Plot the pie chart

# What next?
# Use NLP to identity key words? 
# Topic Modelling
# Reference: https://www.youtube.com/watch?v=aPMPyUoFH8U
# SMV or Logistic Regression for theme classification?


# Question:
# 1) Really need to drop columns in training dataset
# 2) After Model trained, do we still need to remove duplicatue comment?
# 3) As comment data is retrieved daily, do I need to ensure test or new data did not include to training data?
# 4) As it is Amazon data struture only, do I need to modify other customer data as same data structure?

