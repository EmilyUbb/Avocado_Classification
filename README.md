# Avocado Classification and Price Prediction

This project had two main goals, the first was to define and tune a classifcation model that can correctly classify if an avocado is organic or conventional. The second was to define and tune a regression model to predict the price of an avocado based on if it was either conventional or organic, in addition to other features. All Data from this project was gathered directly from the Hass Avocado Board. 

### Design
This project was inspired by the growing popularity of the avocado, and knowledge that most avocados purchased in the United States are imported. In order to improve our agricultural independence more avocados need to be grown in the United States. Using the models developed could be used to entice farmers to grow avocados instead of other agriculture based on their farming set up (organic or conventional), by giving them an idea of potential profitability.

### Data
The dataset contains 20,340 data points with 14 features. After converting the categorical features (Geography) into dummy variables the dataset had a total of 70 features.


### Classification Models

K-nearest neighbors, logistic regression, decision trees, and random forests were used for modeling. Gradient boosted trees, average voting, weighted voting, and max voting were used as ensembling methods. After evaluating all options Gradient Boosted Trees was the best model for classification across both train, and test sets. The best model for Classification was a Random Forest Model. The score on the training data for classification was .9998, and the score on validation data was .9978

### Regression Models

Linear regression, elastic net, ridge regression, lasso regression, random forest regression, and gradient boosting regression were used before settling on random forest regression as the model with the best performance across both train, and test sets. The best model for price predicition was aa Random Forest Regression Model. The score on the training data for price prediciton was .978, and the score on validation data was .848. 

### Model Evaluation

The entire training dataset into 75/25 train vs. holdout, predictions on the 25% holdout were limited to the very end, so this split was only used and scores seen just once.

The final score of the entire pipeline on the hold out data was .927. 
