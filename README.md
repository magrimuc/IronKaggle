# IronKaggle


https://www.kaggle.com/datasets/minasameh55/king-country-houses-aa
The dataset cantains 20 house features plus the price, along with 21613 observations.

The description for the 20 features is given below:

id :- It is the unique numeric number assigned to each house being sold.
date :- It is the date on which the house was sold out.
price:- It is the price of house which we have to predict so this is our target variable and aprat from it are our features.
bedrooms :- It determines number of bedrooms in a house.
bathrooms :- It determines number of bathrooms in a bedroom of a house. ...

### Explaining the machine learning steps and decisions made throughout the project.
7 regressionsmodelle wurden behandelt. 
* Linear Models: 
 Linear Regression,
 Ridge,
 Lasso,
 Logistic Regression (classification?)
* Tree-based (Ensemble) Methods: 
 Decision Tree (AdaBoost),
 Random Forest (Bagging),
 Gradient Boosting,
 XGBoost
 
preprocessing - clean data
split
model choosing
evaluate R**2 score
model performance (data (norm, strd, 1hot enc, label enc, feat engineering, feature sel) -> save() or model (choose another, ensemble, boosting))

iow:
1. Load the dataset.
2. Explore the data to understand its structure — features, target variable, shape, and data types.
3. Clean the dataset (handle duplicates, missing values, etc.).
4. Split the dataset into features (X) and target (y).
5. Explore correlations between the target and features, and among features. Include your interpretations.
6. Handle categorical variables (encoding).
7. Train baseline models such as Linear Regression and KNN Regressor.
8. Evaluate the models using metrics like R² and MAE.
9. Improve your models:
    - Data side: handle outliers, multicollinearity, feature selection, normalization/standardization, feature engineering, etc.
    - Model side: try other models (especially ensemble methods) and perform hyperparameter tuning.
10. Compare all models and select the best one.
11. Identify which features most strongly influence house prices based on your best model.

Deliverables:
- A Jupyter Notebook containing all analysis, code, and results.
- A Presentation (15 minutes) summarizing your ML process, insights, and final model.
- A README file explaining your workflow, reasoning, and key decisions.


jupyter nb - alle Techniken
presentation.
in other words:
A Jupyter notebook detailing the analysis and model for predicting house sales prices.
A mini-presentation outlining the machine learning process used in the analysis.
A README file explaining the machine learning steps and decisions made throughout the project.
Presentation time: 6 - 15min.
