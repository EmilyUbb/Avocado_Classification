# Avocado Classification and Price Prediction
Emily Ubbelohde

## Abstract
The first goal of this project was to define and tune a classification model to classify if an avocado is organic or conventional. The second goal of the project was to define and tune a regression model to predict the price of an avocado based on if it was conventional or organic, in addition to other features. Data was gathered from the Hass Avocado Board, it was then cleaned using python, and models were built using Scikit Learn. 


## Design
This project was inspired by the growing popularity of the avocado, and knowledge that most avocados purchased in the United States are imported. In order to improve our agricultural independence more avocados need to be grown in the United States. Using the models developed could be used to entice farmers to grow avocados instead of other agriculture based on their farming set up (organic or conventional), by giving them an idea of potential profitability.

## Data
The dataset I gathered contains 20,340 data points with 14 features. After converting the categorical features (Geography) into dummy variables the dataset had a total of 70 features. 

## Algorithms

Feature Engineering 
 Converting Geography to dummy variables
 Stripping additional characters for the Type feature


*Classification Models*

K-nearest neighbors, logistic regression, decision trees, and random forests were used for modeling. Gradient boosted trees, average voting, weighted voting, and max voting were used as ensembling methods. After evaluating all options Gradient Boosted Trees was the best model for classification across both train, and test sets..
  
*Regression Models*

Linear regression, elastic net, ridge regression, lasso regression, random forest regression, and gradient boosting regression were used before settling on random forest regression as the model with the best performance across both train, and test sets. 

*Model Evaluation and Selection*


  
The entire training dataset into 75/25 train vs. holdout, predictions on the 25% holdout were limited to the very end, so this split was only used and scores seen just once.

**Model Selection**

**Best Model**
------- 

The best model for Classification was a XG Boosted tree model 
   - Training Score: 99.98%
   - Validation Score: 99.78%

The best model for price prediction was a Random Forest Regression Model  
   - Training Score: .978
   - Validation Score: .848
   - Hold Out Score: .927

   
## Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and Seaborn for plotting

## Summary
- The model produced explains between 85%-92% of the variance between the actual and predicted values for price prediction. Most of that error comes from the price prediction model, less than 1% of that error is passed in from predicting the type of avocado after  defining the classification model.

## Communication
Slides and visuals presented 
