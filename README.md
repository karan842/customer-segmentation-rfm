# Customer Segmentation based on RFM model 😃😆😡

-------------------------------
# About Project📖
   
  This is a data analytics project where the task is to determine customer segmentation. I've collected the data from first technical assessment from TidyQuant company. I gave my best and applied many logics and approaches for that task. Unfortunately I failed in second technical assessment :( So decided to scale up my analytical skills and here is my project for analytics.
  
--------------------
# Approach🛣️:

1. As I told you I've collected a data via assessment.
2. Data was very raw it contained just numbers and it didn't contain any label (Unsupervised data)
3. Found attributes of the data such as null values, mean of total order, revenue, etc. using Pandas.
4. Analyzed the patterns/trends present in the dataset through univariate and bivariate analysis.
5. Found types of customers using Recency, Frequence and Monetary(RFM) model. Here I've search lots of about this RFM techniques from investopedia.com and got reference from GeeksForGeeks.
6. Used matplotib and seaborn to find insights of revenue, orders, momthly revenue/orders insights in the part of Exploratory Data Analysis.
7. Performed data storytelling methodolgy after very insight (you can find this in .ipynb file uploaded above).
8. Cleaned the data and applied feature selection(heatmap) technique for better prediction. 
9. To built machine learning pipline for predicting the types of customers based on features I've scaled the data and trained on multi-label classfication data (which mainly based on RFM model [Champions, Potential Customers, Need Attention] ).
10. Handled imbalacing of the data using Over-Sampling(SMOTE) technique.
11. For better performance I've trained the data on cross-validation and hyperparameter tuning techniques.
12. As is a multi-class based problem I've used KNN(93%) and Naive Bayes(87%). Evaluated the using confusion matrixx and classification report.
13. Build an insightful Tableau Dashboard based on cleaed and well structured data.

-------------------------
# Dashboard Insights📊

<img src='https://github.com/karan842/customer-segmentation-rfm/blob/master/Dashboard.jpg'></img>
