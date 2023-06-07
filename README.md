# Maximum-Credit-Limit-Prediction

This project aims to develop a machine learning model for predicting the maximum credit limit (US Dollar). The credit limits are categorized into four distinct classes. 


Class 1 = credit limit <= 100,000

Class 2 = credit limit > 100,000 & <= 200000

Class 3 = credit limit > 100,000 & <= 300000

Class 4 = credit limit > 300,000

To achieve our objective, I have employed a combination of deep learning and random forest models. 

(1) I utilize deep learning to obtain the probability predictions for each class.

(2) Subsequently, we incorporate these probabilities as new features, alongside the existing ones.

(3) Finally, we feed all the features into the random forest model with hyperparameter tuning for prediction.

## Results

(1) Standalone deep learning : accuracy = 42%

(2) Deep learning + XGBoosting : accuracy = 83%

(3) Deep learning + Randomforest : accuracy = 91%
