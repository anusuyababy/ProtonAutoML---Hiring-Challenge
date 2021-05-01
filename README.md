# ProtonAutoML---Hiring-Challenge


We are providing you a small dataset. There are 2 target variables in it. One is a categorical variable (Target B) and another is numeric variable (Target A). 
You need to split data into 80:20 , training: testing split data, right at the top, the starting. Do a random split. The code should show it.
Then you can clean data , do feature engineering as you like. 
Build any machine learning models on it, but without hyperparameter tuning (since that wont make much difference and we will be running your code). 
All we need is RMSE (root mean squared error) when target is numeric (please do not remove any outliers from Target) and Weighted F1 (balanced F-score) when target is categorical. Note we need these metrics from test dataset (not training)
Dataset - 
https://drive.google.com/file/d/1nMOBIe4xeT68-VPnNBoi7TD4tentz_68/view?usp=sharing


Please note - 
The names of Target A and Target B do not matter. You will be working on automl product and our code is very generic for every dataset. We do the same processes and code on every dataset. So neither feature selection or any processes should not depend on the name of Targets.
A lot of variables need to be converted into features that can be used in machine learning models. That is why this dataset doesn’t contain straightforward numeric variables. 
