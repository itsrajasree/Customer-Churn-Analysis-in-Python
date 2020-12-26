# Customer-Churn-Analysis-in-Python
Analyzing the Churn rate of Customers in Telecom Industry in Python. Regression models are used for finding the best model that fits.

Due to the direct effect on the revenues of the companies, companies are seeking to develop means to predict potential customers to churn. Therefore, finding factors that increase customer churn is important to take necessary actions to reduce this churn. The purpose of this analysis is to develop and design an efficient and effective model for customer churn prediction in the telecommunication industry.

1. Data Preprocessing
In this section, the null values in the dataset are replaced with the mean value. Also, data is grouped based on the datatype of the features.

i. Outlier Removal : Outliers in the columns TotalCharges and Tenure are removed using the InterQuantile Range.

ii. Data Encoding : Label Encoding is used for Encoding the Object columns in the dataset.

iii. Scaling : For scaling the data, MinMax Scaler is used.

iv. Feature Selection : Using the Chi-Square method, the best features in the data are identified.

v. Sampling : Over Sampling is performed in this project. SMOTE method is used.  

2. Data Visualizations
Ploty and Seaborn are the tools used for Exploratory data Analysis.

3. Data Modelling 
For modelling the data; Logistic Regression, Decision Tree, Random Forest, Support Vector Classifier, K- Neighbours Classifier, Multiunomial Naive Bayes, and XG Boost models are used.

Conclusion
Among the models, XG Boost is the best performing model. It provides a better accuracy of 0.83 for training data and 0.82 for test data.
