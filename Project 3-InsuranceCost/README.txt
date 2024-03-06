Business Case

To create a model which can accurately estimate the cost of insurance for individuals based on their attributes.

Python Packages Used

There are different packages used for different purpose. These are mentioned below:

Data Manipulation : Pandas and NumPy packages are used for importing, cleaning and manipulating the dataset.

Data Visualization : Matplotlib and Seaborn packages are used for plotting diagrams and for exploratory data analysis.

Machine Learning : Scikit package is used to build models.

There have been done domain analysis, basic checks, exploratory data analysis,data preprocessing, model building and model evaluation.

Findings from Data

The average age of beneficiary is 39 years. 75 percent beneficiaries are under 51 years of age.
The average number of children covered in health insurance is 1.
The average charge of health insurance is 13270.42(in dollars). The least and maximum charge are 1121.87 and 63770.42(in dollars) respectively.
50.5% of beneficiaries are male.
79.5% of beneficiaries are non-smokers.
Most number of beneficiaries belong to southeast region.
Number of male and female insurance contractor is almost equal, that is 676 male and 662 female. Also the average age of male and female contractor is almost equal.
Most of the beneficiary do not smoke. It can be observed that around 1050 beneficiaries out of 1338 total beneficiary don't smoke.
Southeast region has highest number of beneficiaries and other three regions have almost equal number of beneficiaries.
The average age of beneficiaries who smoke is slightly lesser than those beneficiaries who do not smoke.
The male beneficiaries are paying more charges than the female beneficiaries. The average insurance charge paid by male is 14000(in dollars) and by female is 12000(in dollars).
The beneficiaries having three children are paying highest amount of insurance charge, around 15000(in dollars) on an average. It is followed by beneficiaries having two children. The least amount is being paid by the beneficiaries having five children.
It can be seen from BMI distribution plot that BMI is normally distributed and so 68% of beneficiaries comes under range of 24.57 to 36.75 and 95% of beneficiaries comes under range of 18.48 to 42.84.

Data Preprocessing

I have checked for null values and there is no null values present in any column. 
Besides this, I have checked for duplicated rows and applied label encoding for converting categorical columns into numerical columns.

Models Applied

I have applied several algorithms including linear regression, decision tree, random forest, k-nearest neighbours, gradient boosting, bagging and XGboost. Besides these, I have applied hyperparameter tuning in the case of overfitting.

Model Evaluation

Linear Regression: Testing score-- 0.75 and training score-- 74.5%
Decision Tree: Testing score-- 0.76 and training score-- 100%
Hyperparameter Tuning of Decision Tree: Testing score--86.8 % and training score--84 %
Random Forest: Testing score-- 84% and training score--97.5%
Hyperparameter Tuning of Random Forest: Testing score--85.7 % and training score--91 %
Gradient Boosting: Testing score-- 86.8% and training score-- 90.5%
Linear Regression using Bagging: Testing score-- 74% and training score-- 74%
XGBoost: Tesing score-- 82.7% and training score-- 99%
Hyperparameter Tuning of XGBoost: Testing score-- 86.8% and training score-- 88.4%

Conclusion

Therefore, by looking at the score, we find out that Gradient Boosting, Hyperparmeter Tuning of Decision Tree and Hyperparameter Tuning of XGBoost are the best algorithms to predict insurance charge for individuals based on their attributes.