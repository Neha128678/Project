Business Case

To predict cred score for current credit card customers.
There are three datasets namely, Cust_Account, Cust_Enquiry and Cust_Demographics.

Python Packages Used

There are different packages used for different purpose. These are mentioned below:

Data Manipulation : Pandas and NumPy packages are used for importing, cleaning and manipulating the dataset.

Data Visualization : Matplotlib and Seaborn packages are used for plotting diagrams and for exploratory data analysis.

Machine Learning : Scikit and TensorFlow packages are used to build models.

There have been done domain analysis, basic checks, data preprocessing, model building and model evaluation.

Data Preprocessing

I have preprocessed all three datasets one-by-one. 
I have checked for null values and imputed null values. 
Besides this, I have checked for duplicated rows, applied scaling, dropped unnecessary features and finally merged the all cleaned datasets. Thereafter, I have applied label encoding for converting categorical columns into numerical columns.

Models Applied

I have applied several algorithms including logistic regression, decision tree classifier, random forest classifier, support vector classifier, gradient boosting, naive bayes and support vector classifier. I have also applied hyperparameter tuning.

Model Evaluation

The algorithms and their accuracy score is mentioned below:

Logistic Regression : Testing score-- 60.4% and training score-- 60.8%

Decision Tree : Testing score-- 91.1% and training score-- 100%

Hyperparameter Tuning of Decision Tree: Testing score-- 94.1% and training score-- 97.26%

Random Forest : Testing score-- 95.6% and training score-- 99.9%

XGBoost : Testing score-- 95.5% and training score-- 98.34%

Gradient Boosting : Testing score-- 95.5% and training score-- 95.7%

Naive Bayes : Testing score-- 94.6% and training score-- 94.8%

Support Vector Classifier : Testing score-- 95.6% and training score-- 95.8%

Conclusion

From the above score mentioned, we can say that Support Vector Classifier, Random Forest , XGBoost and Gradient Boosting are the best models for predicting cred score of customers.