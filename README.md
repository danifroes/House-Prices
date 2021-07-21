# House-prices-prediction

- Kaggle Competition to expand skills in advanced regression techniques. 
- With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.
- Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

Steps:
1) Load data from Kaggle competition
2) Analyse categorical and numerial features
3) Baseline: preprocessing pipeline (Simple Imputer, One Hot Encoder, MinMaxScaler), model pipeline (Ridge), score creation and initial prediction
4) Model improved using Ordinal Encoding, Target Engineering and Statistical Feature Selection
5) Models interation: Linear Model, KNN, SVM, Decision Tree, Random Forest, Boosting Trees (AdaBoost and GradientBoost), StackingRegressor and VotingRegressor

At the end, the final submission was done using the best score from StackingRegressor model.
