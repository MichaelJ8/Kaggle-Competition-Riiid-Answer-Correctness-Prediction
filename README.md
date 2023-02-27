# Kaggle-Competition-Riiid-Answer-Correctness-Prediction
In this competition, your challenge is to create algorithms for "Knowledge Tracing," the modeling of student knowledge over time. The goal is to accurately predict how students will perform on future interactions. You will pair your machine learning skills using Riiid’s EdNet data. 

Unfortuantely, I did not leave myself enough time to submit my best model for the compeition, which is shown here, and acheived ~86% AUC on the validation set.
The test set performance was typically ~5% lower than the validation set performance, therefore this model would have acheived ~81% AUC. The best models were composite
models, or ensembled models, between decision tree type models and neural networks. I did  not have time to create a neural network, but a decision tree type model performed very well by itself.
This would have put me in the top 25% of competitors. The key to this performance was the addition of a lagged result variable. The accuracy improves by 10%
if the result of the previous question by the student(see competition description) was included, the lag(1) result being the most useful. 
This notebook is not an example of my programming (it is very stream of consciousness and is not an example of a productionalized model),
it is more of an example of feature engineering that resulted in very good results using only one type of model. 
