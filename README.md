# Airline Customer Satisfaction Prediction using Machine Learning

## Project Overview
This project focuses on predicting customer satisfaction for a major airline using survey data from over 129,000 passengers. The goal was to build a machine learning model that identifies key drivers of satisfaction and accurately predicts whether a future customer is likely to be satisfied based on their flight experience. After modeling and evaluation of Decision Trees, Random Forest, and XGBoost models, Random Forest outperformed with 94.2% Accuracy, 95% precision, 94.5% recall, 94.7% F1-score,and with “seat comfort” emerging as the most influential factor in customer satisfaction.

## Business Understanding
### Stakeholder:
The primary stakeholder is the airline’s customer experience and operations team. Their goal is to proactively improve service quality by identifying what matters most to customers.

### Business Problem:
The airline receives large volumes of customer feedback through post-flight surveys but lacks an efficient system to analyze and act on it at scale. By building a predictive model, the airline aims to:

Identify the top features that drive customer satisfaction

Focus investments on areas that will have the greatest impact (e.g., seating, service quality)

Predict future satisfaction based on passenger profiles and flight characteristics

Understanding and improving customer satisfaction is essential for increasing customer retention and maintaining a competitive edge in the airline industry.

## Data Understanding

### The dataset, Invistico Airlines, contains 129,880 survey responses. Each record includes:

- Passenger information (e.g., class, customer type, age)

- Flight details (e.g., distance, delays)

- Ratings on various services (e.g., seat comfort, food, entertainment)

### Data Cleaning and Preparation:

- Handled missing values and dropped irrelevant columns

- Encoded categorical variables for model compatibility

- Split data into training and testing sets

## Modeling and Evaluation

### Modeling Approach:

- Decision Trees, Random Forest, and XGBoost were selected because of their high accuracy, able to perform on complex data, speed, and performace with structure data.
- Hyperparameters were tuned using GridSearchCV

### Performance Metrics:

- Final Random Forest model achieved an 94.2% Accuracy, 95% precision, 94.5% recall, 94.7% F1-score, indicating strong performance in balancing precision and recall

- Confusion matrix and feature importance plots were used to evaluate and interpret the model

  ![image](https://github.com/user-attachments/assets/eb8b4984-c6ee-4785-9e96-0e957dd4059a)

  
![image](https://github.com/user-attachments/assets/f3cae210-1d67-4281-8c73-3a41ef784222)


### Key Insight:

- “Seat comfort” was the most important feature in predicting satisfaction

- Surprisingly, flight delays did not significantly influence satisfaction, suggesting customers may value in-flight experience more than punctuality

## Conclusion
- The model demonstrates a strong ability to predict customer satisfaction and provides actionable insights for the airline to improve service delivery. Based on the findings, it's recommended that the airline:

- Prioritize improvements in seat comfort and in-flight services

- Use the model to identify at-risk customers and tailor post-flight engagement strategies

## Next Steps:

- Integrate the model into customer feedback platforms for real-time satisfaction prediction

- Collect and analyze longitudinal data to track satisfaction over time

- Explore clustering or segmentation to tailor services to different passenger types










