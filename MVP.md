## Avocado Classification and Price Prediction 
#### Emily Ubbelode

After exploring models for kNN, Logistic Regression, Decision Trees, and Random Forests I have determined that Random Forests is the best model for classifying avocado types. You can see from the decision matrix below that when using random Forests we are able to classify 99.66% of the test data accurately, only misclassifying 2 organic avocados and 12 conventional avocados. 

![Random Forest Confusion Matrix](https://github.com/EmilyUbb/Avocado_Classification/blob/main/rf_confusion_matrix.png?raw=true) 


### Next Steps 

Now that I have accuracy scores and probability for kNN, Logistic Regression, Decision Trees, and Random Forests I will use ensembling to see if I can gain any more accuracy from my model. 

After using ensembling to confirm I have the best possible classification model I will build my Linear Regression model which will predict the price of the Avocado. 


### Other Visualizations 

I have included visualizations of the decision matrices for each model that was tested below. 

![Decision Tree Confusion Matrix](https://github.com/EmilyUbb/Avocado_Classification/blob/main/dt_confusion_matrix.png?raw=true)

![kNN Confusion Matrix](https://github.com/EmilyUbb/Avocado_Classification/blob/main/kNN_confusion_matrix.png?raw=true)

![Logistic Regression Confusion Matrix](https://github.com/EmilyUbb/Avocado_Classification/blob/main/lr_confusion_matrix.png?raw=true)
