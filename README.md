# Churn-prediction
Churn Prediction using Logisitic Regression
Churn Prediction:

Load Data & Packages for model building & preprocessing

Preprocessing & Missing value imputation

Select features on the basis of EDA Conclusions & build baseline model

Decide Evaluation Metric on the basis of business problem

Build model using all features & compare with baseline

We have build a model and cross validated it.
Cross Validation is one of the most important concepts in any type of data modelling. It simply says, try to leave a sample on which you do not train the model and test the model on this sample before finalizing the model.

We divide the entire population into k equal samples. Now we train models on k-1 samples and validate on 1 sample. Then, at the second iteration we train the model with a different sample held as validation.

In k iterations, we have basically built model on each sample and held each of them as validation. This is a way to reduce the selection bias and reduce the variance in prediction power.

Since it builds several models on different subsets of the dataset, we can be more sure of our model performance if we use CV for testing our models.
