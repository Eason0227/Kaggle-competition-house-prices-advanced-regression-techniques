# house-prices-advanced-regression-techniques
Data Analysis Step

Data Prepocessing :
* Check the normality of sale price(QQ plot) and transform to the normal distribution by applying log transformation.
* Convert the numeric varaible to into category varaible(YrSold,MoSold,MSSubClass)
* Check for outliers for numeric features and remove outliers
* Check missing value and imputation (KNN imputation for Numerical varaible, mode imputation for Category data )
* Data standardization 
* Using label encoding for Ordered data (quality, level) ,and one hot encoding for non-sequencial data (MSZoning, Neighborhood)

Modeling : 
* Bulid LinearRegression,Random Forest,SVR,XGBoost,KNN ,Extra Tree,Gradient Boosting and lightGBM and using K-fold cross validation. 
* Choosing XGBoost and SVR to bulid the final model,because they have better performance than other algorithm.
* Tuning model hyperparameter by using Grid Search.
* Mixing predction value of two model to generate final prediciton result.

Final submission result :

* RMSE : 0.11666
* Rank : 91/4257 (Top 3%)
* Time : 2022/6/11

