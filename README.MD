## About The Theory of Planned Behaviour

The theory of planned behaviour assumes that, when an individual intends to perform a specific behaviour, they will actually do so. According to the theory of planned behaviour, behavioural intentions are formed on the basis of attitudes, subjective norms and perceived behavioural control.   

The main argument for this theory is that behaviours are solely determined on behavioural intentions which are determined by behavioural attitude, subjective norms and perceived behaviours. As such, we are going to be examining this theory in detail in this project. 


## My Dataset

I used the Kaggle Electronics Sales Dataset as the dataset to be examined. 
https://www.kaggle.com/datasets/rabieelkharoua/consumer-electronics-sales-dataset/data 


## Data Understanding and Data Preparation 
Data Preparation was conducted in KNIME. with the workflow shown below
![workflow](https://github.com/wongwenbing/Examining-Customer-Purchase-Intent/blob/main/workflow.png)

Mainly, the use of creating synthetic data through SMOTE was crucical in ensuring that the model can perform better with the larger amounts of data.

## Modelling
I used a wide variety of models - Support Vector Machine, Decision Tree, Neural Network, Gradient Boosting to conduct the modelling. After which model comparison was used to examine the models. 

A simple comparison used was comparing the misclassification. In comparing the misclassification, we can observe which model can classify the results **correctly**. 

![misclassification](https://github.com/wongwenbing/Examining-Customer-Purchase-Intent/blob/dc7112291d15c1fc5ba0ee634e63f4885bff2d46/model%20comparison%20misclassification.png)

### Decision Tree 
Having a really good validation score, F1 score, it was crucial to examine the curves.


### Gradient Boosting
Finally, the model selected was the Gradient Boosting Model. Gradient Boosting showed a very positive curve and results. 
#### Lift Curve
![lift](https://github.com/wongwenbing/Examining-Customer-Purchase-Intent/blob/main/lift%20curve.png)

#### ROC Curve
![roc](https://github.com/wongwenbing/Examining-Customer-Purchase-Intent/blob/main/roc%20curve.png)


## Conclusion 
1. Customer Satisfaction emerged as a significant predictor of intent, with higher satisfaction levels strongly correlating with repeat purchases.
2. Product Categories and Pricing played a crucial role in shaping customer preferences, highlighting the importance of tailored marketing strategies.
3. Purchase Frequency clearly indicates brand loyalty, with frequent buyers showing a higher likelihood of continued engagement.
