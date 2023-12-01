# -SyriaTel-Customer-Churn-
# PROJECT PHASE 3
# Overview

SyriaTel, a leading telecommunications company, is grappling with a significant issue of customer churn. The rising number of customers choosing competitors is affecting the company's revenue and market standing. Understanding the reasons behind customer attrition is crucial for the company to adapt. Financial implications are also significant, as customer turnover can lead to lost revenue and acquisition costs. SyriaTel must differentiate itself by offering superior services and addressing customer needs. Data-driven decision-making, customer experience, and satisfaction are key factors. A predictive machine learning model is needed to anticipate customer behavior and identify patterns. A holistic understanding of customer demographics and preferences is also needed. Strategic retention initiatives are also crucial.


# Business Understanding
In the fast-paced telecommunications industry, customer retention is paramount for sustained business success. SyriaTel, a prominent telecommunications company, faces the challenge of minimizing customer churn to optimize revenue and enhance customer satisfaction. The ability to predict and identify customers at risk of leaving is crucial for implementing targeted retention strategies. By leveraging advanced machine learning techniques, SyriaTel aims to build a robust classifier that can predict whether a customer is likely to churn. This classifier will analyze historical customer data, taking into account various features such as call patterns, service usage, and customer interactions. The anticipated outcome is a predictive model that provides valuable insights into factors influencing churn and empowers SyriaTel to proactively address customer needs, reduce attrition, and foster long-term customer loyalty. The ultimate goal is to equip SyriaTel with actionable intelligence, enabling informed decision-making and strategic initiatives to enhance customer retention efforts within the competitive telecommunications landscape.


# Objectives
1.Identifying common characteristics and behaviours associated with customers who have churned


2.Evaluate the importance of different features


3.Develop models and validate their predictive capabilities




# Data Understanding
Data understanding is a crucial step in data science, involving exploring and familiarizing with a dataset to gain insights into its structure, contents, and characteristics. The dataset contains 3333 rows and 21 columns, describing each customer with 21 attributes. The columns include integer types, float types, object types, and a boolean variable 'churn'. The 'churn' column is likely the target variable for a predictive model. Categorical features like'state', 'phone number', 'international plan', and 'voice mail plan' may need encoding for model training. Numerical features include call durations. The dataset appears to have no missing values, as all columns have a count of 3333. The dataset consumes around 524.2 KB of memory. It's worth checking for imbalances in the classes (churned vs. not churned customers) based on the distribution of 'churn' values.


The columns include;


state 


account length


area code


phone number 


international plan voice mail plan 


number vmail messages 


total day minutes, calls, charge 


total eve minutes, calls, charge


total night minutes, calls, charge


total intl minutes, calls, charge


customer service calls 


churn - our target




# Modelling
Exploring a range of models, including logistic regression, decision tree, random forest, and gradient boosting, showcases a comprehensive and systematic approach to addressing the customer churn prediction problem


1. Logistic regression Evaluation

Precision score :0.6857142857142857
Recall score :0.22641509433962265
Accuracy score :0.8892857142857142
F1 score :0.3404255319148936



2.Decision Tree Evaluation

Precision score :0.9107142857142857
Recall score :0.4811320754716981
Accuracy score :0.9285714285714286
F1 score :0.6296296296296295



3.Random Forest Evaluation

Precision score: 0.9792
Recall score: 0.4434
Accuracy score: 0.9286
F1 score: 0.6104



4.Gradient Boost Model Evaluation

Precision score: 0.9828
Recall score: 0.5377
Accuracy score: 0.9405
F1 score: 0.6951




# Conclusion
Highest contributors to Customer Churn include;
Having International Plan ,customers with international plans are more likely to churn
Total number of day minutes , higher usage of daytime minutes is associated with higher churn
High number of customer service calls,customers who make frequent customer service calls are more likely to churn
High number of evening minutes , is correlated to higher churn
Lower contributors include:
Number of voice mail messages,total international calls,state,area code


# Recommendations
--> Investigate the reasons behind the correlation. It could be related to pricing, service satisfaction, or specific features of international plans. Consider targeted retention strategies for customers with international plans.
--> Assess the pricing or service satisfaction related to daytime usage. Consider offering plans that cater to high daytime users or communicating the value proposition of existing plans.
--> Identify the root causes of frequent service calls—these could indicate dissatisfaction or unresolved issues. Focus on improving customer service quality and addressing common pain points.




# Next steps
-->To develop targeted retention strategies based on the insighs gained fron high contributors to churn

