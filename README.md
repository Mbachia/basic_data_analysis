# Tel-Customer-Churn

![Company Logo](https://github.com/Mbachia/Tel-Customer-Churn/raw/main/Company%20Logo/156935176603023900.jpg)

## SyriaTel Customer Churn Analysis

# Overview

SyriaTel is a telecommunications company in Syria. They have been informed that some of their customers have started to discontinue their service. This analysis will determine what features will indicate if a customer will discontinue their service.

## Problem Statement
Syria Tel, a prominent telecom company, is facinf challenges of customers discontinuing their service.  This as a result affects the company's stability and income. The problem lies in predicting when customers might leave and understanding why they choose to do so. Syria Tel wants to prevent this from happening and keep their customers satisfied.

## Main Objective
To apply classification modeling techniques to analyze customer churn data for Syria Tel, aiming to identify the  factors contributing to customer churn. 

## Subjective Objectives
1. Explore the Data for Classification
Explore the dataset to understand the relationships between different variables and the target variable (customer churn).

2. Create a Classification Model for Churn Prediction
Build a classification model (i.e Logistic Regression, Random Forest) to predict customer churn. 

3. Analyze Feature Importance and Effects
Analyze the importance of independent features in predicting churn. Identify the most influential factors affecting churn prediction based on the model's coefficients, feature importance scores, or other relevant metrics.

4. Assess Model Performance and Reliability
Evaluate the classification model's performance through metrics like accuracy, precision, recall, and confusion matrix. Ensure the model is reliable and accurately predicts customer churn by testing.

5. Offer Practical Insights and Recommendations
Provide actionable insights and recommendations based on the classification model's findings. Offer guidance to telecom companies on factors influencing customer churn.

## Data Understanding

The dataset has the following columns:

state, account length,area code,phone number,international plan,voice mail plan, number vmail messages,total day minutes,total day calls,total day charge, total eve minutes, total eve calls,total eve charge, total night minutes,total night calls,total night charge,total intl minutes,total intl calls,total intl charge,customer service calls,churn.

# Results and interpretation

## Baseline Model:

Accuracy:
The accuracy of the model is 87.03%. This metric signifies the overall correctness of predictions made by the model. In this case, the model correctly predicted approximately 87 out of every 100 instances, which seems reasonably high at first glance.

## Random Forest Classifier:

Accuracy:
The model's accuracy is 89.40%. It gets around 89 out of 100 right.

Best Parameters Found: The best settings for this model are max_depth: None, min_samples_split: 2, n_estimators: 200. After changing these settings, the model's accuracy goes up to 89.80%.

## XGBoost Classifier
The accuracy of the model is 91.24%. This indicates the overall correctness of predictions made by the model. It correctly predicted approximately 91 out of every 100 instances, showcasing a higher accuracy compared to previous models.

## Conclusions
**Model Performance:** 

The XGBoost model demonstrated the highest accuracy among the models evaluated, achieving an accuracy of approximately 91%.
Random Forest and Logistic Regression also performed reasonably well, achieving accuracies of around 89% and 87% respectively.

**Prediction of Churn:**

The models showcase potential in predicting customer churn, providing insights into identifying customers at risk of churning.
They help in understanding the influential factors affecting churn, aiding in proactive strategies to retain customers.

**Key Predictors of Churn:**

Features such as 'customer service calls,' 'international plan,' and 'total day minutes' appear to be significant factors influencing customer churn based on the model coefficients.

**Investigate international plan churn rate**

The substantial churn rate among international plan holders signals the need for focused efforts in implementing personalized retention strategies to retain these customers effectively.

## Recommendations

**Targeted Retention Strategies:**

Utilize insights from the models to implement targeted retention strategies for customers identified as high-risk churners.
Offer personalized incentives or services to retain customers with characteristics that indicate a higher likelihood of churning.

**Improved Customer Service:**

Focus on improving customer service quality as the number of customer service calls is a significant predictor of churn.
Address issues or concerns promptly to enhance customer satisfaction and loyalty.

**Continuous Monitoring and Model Refinement:**

Continuously monitor model performance and update it with new data to ensure its reliability and accuracy.

**Explore strategies for international plans:**

With over 42% of international plan holders churning, it's crucial to explore tailored retention strategies for this segment to improve customer retention rates.

