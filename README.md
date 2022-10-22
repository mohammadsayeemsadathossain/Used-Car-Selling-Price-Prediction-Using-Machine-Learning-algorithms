# Used-Car-Selling-Price-Prediction-Using-Machine-Learning-algorithms:
 - Used dataset from kaggle named "Vehicle" and applied data cleaning, data preprocessing and finally predicted the prices of the used car info available in the dataset.
 - Finally written a report in IEEE format, stating the limitations and scopes of future work too.

Dataset link: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?resource=download

N.B: We have changed some entries of the original dataset since we wanted to impose more reality into it by clearing some datas since some fields may be mistyped or null as these are just results of some questionnaires by owners of the used cars. So, to make our data preprocessing work, we cleared some data. 

Data Pre Processing Techniques used:
 - Deleting duplicate and null values
 - Imputation of missing values
 - Feature Engineering
 - Feature Normalization/Scaling
 - Feature Selection

Since the predicted value is a continuous value, i.e the selling price, the type of machine learning that this project applies to is Regression.
Machine Learning models used:
 - Linear Regression
 - Decision Tree Regression
 - Random Forest Regression
 - Gradient Boosting Regression

Accuracy Metrics used:
 - R2 Score
 - Mean Absolute Error, MAE
 
We see the highest accuracy score was achieved using Gradient Boosting, hence we use this algorithm to actually predict the price of a used car given to us by any user, which can be of any model and year.

# The whole step-by-step process is written cleanly in the report uplaoded in the main branch.
