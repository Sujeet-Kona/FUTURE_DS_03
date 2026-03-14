# FUTURE_DS_03

Marketing Funnel & Conversion Performance Analysis
Project Overview

This project analyzes user behavior on an e-commerce platform to understand how customers move through the conversion funnel from product viewing to purchase.

The goal is to identify drop-off points in the marketing funnel, analyze customer interaction patterns, and build a machine learning model to predict purchase probability during a session.

The project demonstrates how data analytics and machine learning can support business decisions to improve conversion rates and increase revenue in e-commerce platforms.

Dataset

This project uses the E-Commerce Behavior Data from Multi-Category Store.

Dataset link:
https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

The dataset contains millions of real user interaction events collected from a large online retail platform.

Dataset Features
Column	Description
event_time	Timestamp of user interaction
event_type	Type of interaction (view, cart, purchase)
product_id	Unique product identifier
category_id	Product category identifier
category_code	Product category name
brand	Product brand
price	Product price
user_id	Unique user identifier
user_session	Session identifier

Each row represents a single user interaction event on the platform.

Project Objectives

The main objectives of this analysis are:

• Understand customer interaction behavior on the platform
• Analyze the conversion funnel from product view to purchase
• Identify key factors influencing purchase decisions
• Build a machine learning model to predict purchase outcomes
• Generate data-driven business insights and recommendations

Tools & Technologies

The project was implemented using the following tools:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Project Workflow

The project follows a standard data analytics pipeline.

1 Data Cleaning

• Removed unnecessary columns
• Handled missing values
• Optimized memory usage for large dataset processing

2 Exploratory Data Analysis (EDA)

The exploratory analysis focused on understanding:

• Distribution of user events
• Product price behavior
• Category popularity
• User interaction patterns

3 Conversion Funnel Analysis

Customer journey stages were analyzed to identify conversion bottlenecks.

Customer funnel stages:

View → Cart → Purchase

The funnel analysis helps identify where users drop off before completing purchases.

4 Feature Engineering

Session-level behavioral features were created to capture user intent and engagement.

Key engineered features include:

• Number of product views per session
• Number of cart interactions
• Average product price exposure
• Total event count per session
• Cart-to-view ratio
• Engagement score

These features represent user interest and purchase intent.

5 Machine Learning Modeling

Machine learning models were built to predict whether a session will result in a purchase.

Models used:

• Logistic Regression
• Decision Tree
• Random Forest
• Gradient Boosting

Model evaluation metrics:

• Accuracy
• Precision
• Recall
• F1 Score
• ROC Curve

Key Visualizations
Event Type Distribution

Shows the distribution of user interaction types across the platform.

Customer Conversion Funnel

Illustrates the flow of users from product viewing to purchase.

Feature Correlation Matrix

Shows relationships between engineered behavioral features.

Model Performance Comparison

Compares the performance of different machine learning models.

Random Forest Feature Importance

Identifies which behavioral features most strongly influence purchase prediction.

Key Business Insights
1 Large Drop-Off at Early Funnel Stage

Most users only view products but do not proceed to cart or purchase, indicating a major drop-off early in the customer journey.

2 Cart Interactions Are Strong Predictors of Purchase

Sessions that include cart additions are significantly more likely to result in purchases, highlighting the importance of encouraging cart interactions.

3 High Engagement Sessions Convert More

Users with higher interaction counts and product exploration behavior show higher purchase probability.

4 Price Exposure Influences Conversion

Users interacting with higher-priced products may require additional trust signals such as product reviews or promotional offers before completing a purchase.

Business Recommendations

Based on the analysis, the following strategies could improve conversions:

• Improve product page design and user experience
• Encourage cart additions through targeted promotions
• Provide personalized product recommendations
• Simplify the checkout process
• Target high-intent users with marketing campaigns
