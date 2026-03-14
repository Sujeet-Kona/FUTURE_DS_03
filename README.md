# FUTURE_DS_03

Marketing Funnel & Conversion Analysis
E-Commerce User Behavior Analytics Project
Project Overview

This project analyzes customer behavior in an e-commerce platform to understand how users move through the conversion funnel from product view to purchase.

The goal is to identify drop-off points in the funnel, understand user engagement patterns, and build a machine learning model that predicts the probability of purchase during a session.

By combining exploratory data analysis, behavioral feature engineering, and machine learning, the project demonstrates how data can be used to support conversion optimization and revenue growth strategies.

Dataset

The analysis uses the E-Commerce Behavior Data from Multi-Category Store.

The dataset contains millions of user interaction events from an online store.

Key Variables
Column	Description
event_time	Timestamp of user action
event_type	User interaction (view, cart, purchase)
product_id	Product identifier
category_code	Product category
brand	Product brand
price	Product price
user_id	Unique user identifier
user_session	Session identifier
Project Workflow

The project follows a real-world data analytics pipeline.

1 Data Cleaning

Removed unnecessary columns

Handled missing values

Optimized memory usage

2 Exploratory Data Analysis

Event type distribution

Product price analysis

Category popularity

User behavior patterns

3 Funnel Analysis

Customer journey stages were analyzed:

View → Cart → Purchase


This helped identify conversion bottlenecks in the user journey.

4 Feature Engineering

Session-level features were created to capture user behavior:

Number of product views

Number of cart interactions

Average price exposure

Event count per session

Cart-to-view ratio

Engagement score

These features help model purchase intent.

5 Machine Learning Modeling

Multiple models were trained to predict whether a session will result in a purchase.

Models used:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

The models were evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC Curve

Key Visualizations
Event Type Distribution

Customer Conversion Funnel

Feature Correlation Matrix

Machine Learning Model Comparison

Feature Importance (Random Forest)

Key Business Insights
1 Most Users Only Browse Products

A large proportion of user interactions are product views, with relatively fewer cart additions and purchases.

This indicates significant drop-off early in the customer journey.

2 Cart Activity Strongly Predicts Purchases

Sessions containing cart interactions are much more likely to result in purchases.

Encouraging users to add items to the cart can increase conversion rates.

3 High Engagement Sessions Convert More

Users with higher session engagement (more interactions) show higher purchase probability.

Personalized recommendations could further increase engagement.

4 Price Exposure Influences Purchase Behavior

Users interacting with higher priced products may require additional trust signals such as reviews or discounts before purchasing.

Business Recommendations

Based on the analysis, the following strategies could improve conversions:

Improve product page design and calls-to-action

Provide personalized product recommendations

Introduce promotional offers for cart additions

Simplify checkout processes

Use targeted marketing for high-intent users

TECHNOLOGY USED:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
