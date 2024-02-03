Business Case

The task is to predict whether people got H1N1 and seasonal flu vaccines using information they shared about their backgrounds, opinions, and health behaviors. There are two target columns namely h1n1_vaccine and seasonal_vaccine.

Python Packages Used

There are different packages used for different purpose. These are mentioned below:

Data Manipulation : Pandas and NumPy packages are used for importing, cleaning and manipulating the dataset.

Data Visualization : Matplotlib and Seaborn packages are used for plotting diagrams and for exploratory data analysis.

Machine Learning : Scikit and TensorFlow packages are used to build models.

There have been done domain analysis, basic checks, exploratory data analysis,data preprocessing, model building and model evaluation.

Findings from Data

Most of the people are of age group 65+ yrs.
37.8% of the people are graduate.
57.3% of the people belong to above poverty income group.
59.3% of the total population are female and 40.7% are male.
53.7% of the people are employed.
Most of the people (ie, around 10,000 people) are somewhat concerned and few of them (ie, around 8,000 people) are not very concerned of the H1N1 flu.
Most of the people (around 14,000 people) have little knowledge about H1N1 flu.
94% of the people (around 25,000 people) has not taken antiviral medications.
71% of the people has avoided close contact with others with flu-like symptoms.
60% of the people has not been recommended Seasonal flu vaccine by the doctor.
Most of the people (around 45% of people) believes that H1N1 vaccine is somewhat effective and 26% of people belives that H1N1 vaccine is very effective.
37.5% people believe that the risk of H1N1 vaccine is somewhat low and 30% of people believe that risk of H1N1 vaccine is very low. In other words, we can say that 67.5% of the people believe that the risk of H1N1 vaccine is low. 29% of the people believe that the risk of H1N1 vaccine is high.
44.5% of the people believe that seasonal flu vaccine is somewhat effective and 37.5% people believe that seasonal flu vaccine is very effective. 14.6% of the people believe that seasonal flu vaccine is low effective.
35% of the people believe that risk of seasonal flu vaccine is somewhat low. It is followed by the people (29.5%) who belives that the risk of seasonal flu vaccine is somewhat high.
Most of the people are of age group 65+ yrs. It is followed by the people of the age group 55- 64 years.

Data Preprocessing

I have checked for null values and imputed null values. 
Besides this, I have checked for duplicated rows and applied label encoding for converting categorical columns into numerical columns.

Models Applied

I have applied several algorithms including logistic regression, decision tree classifier, random forest classifier, support vector classifier, gradient boosting and naive bayes. We have also applied hyperparameter tuning in case of overfitting. Also, used technique of feature extraction with the help of Principal Component Analysis(PCA).

Model Evaluation 

For h1n1 prediction model
Logistic Regression : Testing score-- 72.5% and training score-- 73%

Decision Tree : Testing score-- 78% and training score-- 99%

Hyperparameter Tuning of Decision Tree: Testing score-- 84% and training score-- 85%

random Forest : Testing score-- 82% and training score-- 100%

Hyperparameter Tuning of Random forest : Testing score-- 85% and training score-- 99%

Gradient Boosting : Testing score-- 81% and training score-- 81%

Naive Bayes : Testing score-- 77% and training score-- 77%

Support Vector Classifier : Testing score-- 78% and training score-- 78%

Random forest (PCA) : Testing score-- 70% and training score-- 100%

Logistic Regression ( PCA) : Testing score-- 39% and training score-- 40%

Decision Tree (PCA) : Testing score-- 66% and training score-- 100%

For Seasonal Vaccine prediction model
Logistic Regression : Testing score-- 71% and training score-- 72%

Decision Tree : Testing score-- 67% and training score-- 100%

Hyperparameter Tuning of Decision Tree: Testing score-- 74% and training score-- 76%

random Forest : Testing score-- 83% and training score-- 100%

Hyperparameter Tuning of Random forest : Testing score-- 77.8% and training score-- 99%

Gradient Boosting : Testing score-- 78% and training score-- 78%

Naive Bayes : Testing score-- 70.5% and training score-- 70.7%

Support Vector Classifier : Testing score-- 78% and training score-- 78%

Random forest (PCA) : Testing score-- 65% and training score-- 100%

Logistic Regression ( PCA) : Testing score-- 56% and training score-- 55%

Decision Tree (PCA) : Testing score-- 61% and training score-- 100%

Conclusion

From the above score mentioned, we can say that Hyperparameter Tuning of Decision Tree is the best model for h1n1 vaccine prediction and Gradient Boosting is best model for seasonal vaccine prediction.
