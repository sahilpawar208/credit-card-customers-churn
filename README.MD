# Credit Card Customer Churn Project
## **Introduction**
Acquiring new customers can be a costly endeavor for businesses, and retaining existing customers is crucial for sustained growth. Predicting customer churn is therefore an important capability for businesses, as it enables them to proactively identify at-risk customers and offer targeted services or interventions to prevent them from leaving.

The objective of this project is to develop a machine learning model that predicts customer churn for a credit card service using various customer information variables. Specifically, we aim to identify which variables are most predictive of churn, and to build a model that can accurately classify customers as either likely to churn or likely to remain with the service.

## **Data**
 we used the [Credit Card Customers dataset](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers), which includes information on approximately 10,000 credit card customers, such as age, gender, education level, marital status, and more. 

 The data required minimal cleaning, and we were able to use most of the features for modeling. However, we did drop some unnecessary columns, such as customer ID, that would not contribute to our analysis.

 ## **Approach**
 We first performed [exploratory data analysis (EDA)](https://github.com/MisssssLegendary/Credit_Card_Customer_Churn/blob/main/EDA_and_visualization.ipynb) to identify patterns and relationships between features and the target variable, customer churn. We used various visualization techniques to help us identify key features that are most predictive of churn, and to gain a better understanding of our data.

 Next, we explored [various encoding, oversampling, and normalization methods](https://github.com/MisssssLegendary/Credit_Card_Customer_Churn/blob/main/Feature_engineer_%26_Over_sampling_%26_Scaling.ipynb) to determine which techniques work best for our dataset. 

 At last, we [built a machine learning model](https://github.com/MisssssLegendary/Credit_Card_Customer_Churn/blob/main/ML_Model_Building_and_Hyperparameter_Tuning.ipynb) to predict customer churn using the Gradient Boosting classifier. We used AutoML and Gridsearch to perform hyperparameter tuning on the model, further optimizing its performance. We also used various techniques to evaluate the model's performance, such as cross-validation and ROC-AUC score.

 ## **Results**
 Our final model achieved a ROC-AUC score of 0.9936, indicating that it is a highly effective predictor of customer churn. By using this model, businesses can proactively identify and retain customers, helping to improve customer satisfaction and reduce the costs associated with customer acquisition. Through our analysis, we identified several key features that are highly predictive of customer churn, including total transaction amount, number of transactions, and age.

 ## **Conclusion**
 In conclusion, we have developed a highly accurate machine learning model that can predict customer churn for a credit card service. By leveraging the power of AutoML and Gridsearch, we were able to optimize our model's performance and achieve a significant improvement in accuracy. Our analysis identified several key features that are highly predictive of churn, which can help businesses proactively identify and retain customers. Overall, this project has the potential to improve customer satisfaction and reduce costs associated with customer acquisition for businesses.