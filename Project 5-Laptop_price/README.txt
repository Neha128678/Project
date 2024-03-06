Business Case

The task is to create a model which can estimate the price of laptops based on their attributes.

Python Packages Used

There are different packages used for different purpose. These are mentioned below:

Data Manipulation : Pandas and NumPy packages are used for importing, cleaning and manipulating the dataset.

Data Visualization : Matplotlib and Seaborn packages are used for plotting diagrams and for exploratory data analysis.

Machine Learning : Scikit package is used to build models.

There have been done domain analysis, basic checks, exploratory data analysis,data preprocessing, model building and model evaluation.

Findings from Data

The average price of laptop is 1123.686992 euros and the highest price of sold laptop is 6099 euros.
Laptops manufactured by 'Dell' have been sold most.
Laptops of category 'Notebook' have been bought most.
Laptops with screen resolution of 'Full HD 1920x1080' have been bought most.
Laptops with CPU 'Intel Core i5 7200U 2.5GHz' have been bought most.
Laptops with RAM '8 GB' have been sold most.
Laptops with memory of '256GB SSD' have been bought most.
Laptops with GPU of 'Intel HD Graphics 620' have been bought most by consumers.
Laptops with operating system 'Windows 10'have been sold most.
Laptops with weight of 2.2 kg have been bought most by buyers.
Laptop belonging to brand Dell and Lenovo are sold maximum.
Huawei laptops are sold least.
Price of brand Razer laptop is highest. Price of laptop belonging to LG is second highest.
Price of Vero laptop is least.
Laptop of category "Notebook" are sold maximum in number, followed by "Gaming".
Price of laptop of category "Workstation" is highest. It is followed by "Gaming" laptop.
Laptops with 8 GB RAM are sold maximum. It is followed by sale of 4 GB and 16 GB RAM laptop.
Price of laptop with 64 GB is highest. It is followed by price of 32 GB and 24 GB.
Laptops with operating system 'Windows 10' have been bought most. It captures huge share of market.
Price of operating system 'mac OS' is highest, followed by 'Windows 7'.
Laptop with screen resolution 'Full HD 1920x1080' have been sold most.
Laptops without feature of touchscreen have been bought most because of price difference as price of touchscreen laptop is higher than that of no touchscreen laptop.
Laptops with CPU 'Intel Core i5 7200U 2.5GHz' have been sold most.
Laptops with '256GB SSD' have been sold most. It is followed by laptops with 1TB HDD.
Laptops with GPU 'Intel HD Graphics 620' have been bought most.

Data Preprocessing

I have checked for null values and no any null values are present in any column. 
Also feature engineering have been done and some new columns named 'PPI', 'HDD', 'SSD', 'Hybrid', 'Flash Storage' using given features.
Besides this, I have checked for duplicated rows and dropped duplicated rows, applied scaling and applied label encoding for converting categorical columns into numerical columns.

Models Applied

I have applied several algorithms including linear regression, decision tree regressor, random forest regressor, gradient boosting. I have also applied hyperparameter tuning in case of overfitting.

Model Evaluation

The algorithms and their accuracy score is mentioned below:

Logistic Regression : Testing score-- 74.1% and training score-- 70.52%

Decision Tree : Testing score-- 71.4% and training score-- 99%

Hyperparameter Tuning of Decision Tree: Testing score-- 74% and training score-- 92.7%

Random Forest : Testing score-- 83% and training score-- 97%

Hyperparameter Tuning of Random forest : Testing score-- 88.66% and training score-- 97.9%

Gradient Boosting : Testing score-- 87.18% and training score-- 93%

Conclusion 

From the above score mentioned, we can say that Hyperparameter Tuning of Random Forest is the best model for laptop price prediction. Besides this, Gradient Boosting is the second best model.