# CTR_Example
An example Click Through Rate Prediction Implementation

Some issues worth mentioning:

Given model has been implemented for the purpose of an example demonstration of an end-to-end pipeline architecture for the problem of predicting Click-Through Rate assignment with a given dataset from avazu/kaggle. The data can be found via: https://www.kaggle.com/c/avazu-ctr-prediction/data 

The most considerable constraint of this model would be the expensiveness of the features processing, once the features have been passed through ETL procedures and reach to the step of multi dimension reduction via PCA, due to the hardware capabilities, a sub dataset which contains 100k rows have been used to relax the limited resource constraint. The chosen model is a random forest algorithm in order to avoid possible overfitting effect on the model. The test results have been taken as Error = 0.37073930085588924 , even though the model uses very limited resources by the meaning of total number of data and features. This indicates the model is OK, however definitely open for later improvements and more tuning.
