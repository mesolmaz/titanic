## Titanic: Machine Learning from Disaster - Predicting Survival Rate of Titanic Passengers
by Mehmet Solmaz <br> March 2020

This is my take on Kaggle Titanic Competition (https://www.kaggle.com/c/titanic/overview). I submitted the outcome of this code and obtained a score of __0.78468__. 

### Methodology
Everything needed to understand the challenge and the data is in this link: https://www.kaggle.com/c/titanic/.<br>
The data is given as Train and Test data. There is useful data that is missing rows. There is some not so useful data that can be discarded. Feature engineering is a must. Here are the main steps I followed:

1. Data wrangling, and understanding data. 
2. Impute missing data and create extra features.
3. Use XGBoost as Binary classifier and mean Cross_Val_Score as metric
4. Bayesion Optimization to optimize hyper-parameters. 

### Results and Evaluation

1. Mean Cross Validation Score of __0.8283__ on training set
2. Test score of __0.7847__ (Slightly overfitted model) 

My first submission had a score of 0.76076 and I was able to improve it by 2% using feature engineering and hyper-parameter optimization.