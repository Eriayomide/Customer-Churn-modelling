# Customer-Churn-modelling
This project takes all inclusive approach to determine customers who are likely to churn based on certain criteria
The following approach were used in solving the problem
1.Define churn – Churn is defined as any customer who didn’t make any purchase within the last 8 months of Business transaction i.e. any customer whose maximum/last transaction date is less than 31/10/2007. 
2.Carry exploratory analysis to understand the profile of churners using their demographic, transactional and attitudinal data. You can employ a decision tree to generate a rule set that can help you describe these customers or plot a distribution of the demographic variables vs the Churn variable (target)
3.As part of your feature engineering, I use RFM analysis to create recency, frequency and monetary(lifetime value) attributes for each customer. Using the derived RFM variables or RFM Scores, I create a clustering model (unsupervised technique) using K means or other clustering algorithms to generate customer segments (clusters – use elbow method to select the best number of clusters). The cluster variable is used as part of my modelling and scoring variables.
Churn variable is my target variable for my modelling task
4. I make sure I have a single customer view i.e the final dataset must have a single customer data per row no duplicates 
Follow the modelling phases including, statistical testing(Chi-square tests, correlations etc) to test for multi collinearity and over fitting, investigate the distributions, Identify outliers, extreme values or spurious values, impute missing values where applicable, Carry out feature selection, partition the data into training, testing or validation or use cross validation technique, develop various models and select champion model
5.I Deploy or score model on an unseen dataset/hold out sample, this dataset must not be included in the model development phase.
6. Finally, I revalidate your model before rolling out the main marketing campaign (A/B testing is applicable for a response model)
