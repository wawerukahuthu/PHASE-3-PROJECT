# PHASE-3-PROJECT
SyriaTel Customer Churn Prediction

Project Overview

This project aims to predict whether a customer will soon stop doing business with SyriaTel, a telecommunications company. Customer churn is a significant challenge for the telecom industry, as losing customers directly impacts revenue. By building a predictive model, SyriaTel can identify customers at risk of churning and implement targeted retention strategies to reduce churn and improve customer satisfaction.

Objective

The objective is to build a binary classification model that predicts whether a customer will churn based on various features related to customer behavior, service usage, and account information. The project includes data preprocessing, exploratory data analysis (EDA), model development, and evaluation.

Data

The dataset used in this project is titled "Churn in Telecom's dataset" and contains features such as:

Demographics: Information like age, gender, etc.

Account Information: Contract details, tenure, and payment methods.

Service Usage: Metrics such as the number of calls, data usage, and more.

Customer Service Interactions: Number of customer service calls, complaints, etc.

The target variable (churn) indicates whether a customer has churned (1) or not (0).

Key Features

The following key features were identified as crucial in predicting customer churn:

Tenure: The length of time a customer has been with the company.

Monthly Charges: The amount charged to the customer on a monthly basis.

Total Charges: The total amount charged over the customer's entire tenure.

Contract Type: Whether the customer is on a month-to-month, one-year, or two-year contract.

Customer Service Calls: The number of calls made by the customer to customer service.

These features were selected based on their importance in the predictive model and their relevance to customer churn behavior.

Models

Two models were developed and evaluated:

Logistic Regression: A simple yet effective model for binary classification tasks.

Decision Tree Classifier: A model that can capture non-linear relationships in the data.

Both models were evaluated using accuracy, precision, recall, F1 score, confusion matrix, and ROC-AUC metrics. Based on the evaluation, the best-performing model was chosen.

Evaluation Metrics

Accuracy: Measures the percentage of correct predictions.

Precision: Indicates the proportion of positive identifications that were actually correct.

Recall: Measures the ability to find all positive instances.

F1 Score: The harmonic mean of precision and recall.

Confusion Matrix: A table showing the true positives, false positives, true negatives, and false negatives.

ROC-AUC: A performance metric that considers both the true positive rate and false positive rate.

Final Recommendations for SyriaTel

Based on the analysis and model findings, the following recommendations are proposed to reduce customer churn:

Develop Targeted Retention Strategies:

Focus on customers with shorter tenures and those on month-to-month contracts, as they are more likely to churn. Offering loyalty programs or incentives for long-term commitments can help retain these customers.

Enhance Customer Experience:

Customers who make frequent customer service calls are more likely to churn. Improve the customer service experience by reducing wait times, resolving issues more effectively, and proactively addressing common complaints.
Promote Long-Term Commitments:

Customers on longer contracts (e.g., one-year or two-year contracts) are less likely to churn. Encourage customers to sign longer-term contracts by offering discounts or additional benefits for committing to a longer period.
Optimize Pricing and Value Communication:

Monthly charges and total charges are significant factors in churn. Ensure that pricing is competitive and that customers feel they are receiving good value for the price they pay. Consider offering tailored plans that better meet the needs of different customer segments.
Leverage Predictive Analytics:

Continuously monitor the predictive model's performance and update it as new data becomes available. Use the model to proactively identify at-risk customers and intervene before they decide to leave.
By implementing these recommendations, SyriaTel can proactively address the key factors driving customer churn, ultimately improving customer retention and reducing revenue loss.

Repository Structure

data/: Contains the dataset used for this project.

notebooks/: Jupyter notebooks with EDA, modeling, and evaluation.

models/: Saved models and preprocessing pipelines.

reports/: Contains the final report and presentation slides.

scripts/: Python scripts for data processing and model evaluation.

README.md: Project documentation and instructions.

How to Run the Project

Clone the repository.

Install the necessary dependencies from requirements.txt.

Run the Jupyter notebooks for data exploration and modeling.

Evaluate the models using the provided scripts.

Conclusion

This project demonstrated the effectiveness of predictive modeling in identifying customers at risk of churning. By implementing the recommendations and continuously refining the model, SyriaTel can reduce churn, increase customer satisfaction, and improve profitability.