## About The Theory of Planned Behaviour

The theory of planned behaviour states that this that and the other is supposed to happen. 

## My Dataset

I used the Kaggle Electronics Sales Dataset as the dataset to be examined. 
https://www.kaggle.com/datasets/rabieelkharoua/consumer-electronics-sales-dataset/data 


## Data Understanding and Data Preparation 
Data Preparation was conducted in KNIME. with the workflow shown below
![workflow](https://github.com/wongwenbing/Examining-Customer-Purchase-Intent/blob/main/workflow.png)

Mainly, the use of creating synthetic data through SMOTE was crucical in ensuring that the model can perform better with the larger amounts of data.

## Modelling
I used a wide variety of models - Support Vector Machine, Decision Tree, Neural Network, Gradient Boosting to conduct the modelling. After which model comparison was used to examine the models. 

### Decision Tree 
Having a really good validation score, F1 score, it was crucial to examine the
