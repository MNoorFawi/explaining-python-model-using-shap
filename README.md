## Using SHapley Additive exPlainations (SHAP) Library to Explain Python ML Models
Almost always after developing an ML model, we find ourselves in a position where we need to explain this model. Even when the model is very good, it is still a black box that needs to be deciphered. Explaining a model is a very important step in a data science project that we usually overlook. [SHAP library](https://github.com/slundberg/shap) helps in explaining python machine learning models, even deep learning ones, so easy with intuitive visualizations. It also demonstrates feature importances and how each feature affects model output.

Here we are going to explore some of SHAP’s power in explaining a Logistic Regression model.

We will use the [Bank Marketing dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#)[1] to predict whether a customer will subscribe a term deposit.

#### Full explanation of the code in https://minimatech.org/explain-python-machine-learning-models-with-shap-library/

###### [Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014
