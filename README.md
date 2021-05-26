# machine-learning-challenge
Logistic Regression and SVC Models

Both the Logistic Regression model and the SVC model had very similar results, despite having different parameters used for the X data. I am unsure why, but the SVC model saw very
few changes in score after hyperparameter tuning, as every combination of hyperparameters yielded very similar results. The Logistic Regression model did see changes in score, but
they were minimal. I wouldn't recommend using either to identify new exoplanets. The most likely solution to get a more accurate model would be to select different features of the
dataset for the X data, as the features used in this model may carry little weight when it comes to determining an exoplanet.

Deep Learning Model

The Deep Learning model had fairly improved results over the other two. This could be due to the increased amount of features selected (5) and the more advanced model. Even without
the hyperparameter tuning, the deep learning model had better testing data scores (.58) than the Logistic Regression and SVC models. Of the three models, I would most recommend
this one to identify new exoplanets, but it could use even further improvements with correct hyperparameter tuning.
