# Introduction
Data imbalance across classes is a common cause of classification problems. This is the case when the size of examples from one class is significantly larger or smaller than the size of examples from the other classes. Many of these problems benefit from classifiers that perform well on the minority class. Using out-of-the-box classifiers for such problems may result in suboptimal results in terms of this goal. Here we studied and implemented several techniques for boosting classification performance with imbalanced datasets.
# Real-life areas of implications
1) Fraud detection
2) Disease Diagnosis
3) Product categorization

# Problem statement
In this project, we will handle an imbalance in data using various techniques and improve the f1-score. We will use the dataset from Kaggle of Telco Customer Churn, in which we predict Customer churn, i.e. to measure why customers are leaving a business. In this project, we will be looking at customer churn in telecom business. We will build a deep learning model to predict the churn and use precision, recall, and f1-score to measure the performance of our model.

# Datasets
The dataset used in our project is from Kaggle, the Telco Customer Churn dataset. In this dataset, the churn attribute is unbalanced, according to which we have to do classification. The data set includes information about:
• Customers who left within the last month – the column is called Churn
• Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
• Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
• Demographic info about customers – gender, age range, and if they have partners and dependents.

# Methodologies and Results
We will use different methodologies to train our imbalanced dataset we have taken into consideration. Now you can see that the f1 score is very less. Because of the unbalanced dataset. Now to improve it, we will use the following approaches to implement to get results over the unbalanced dataset:
■ Random Undersampling
■ Random Oversampling
■ Synthetic Minority Oversampling Technique (SMOTE)
■ Ensemble Learning

