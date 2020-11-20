# Neural Network Charity Analysis

## Challenge Overview
With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Resources
- [charity_data.csv](resources/charity_data.csv)
- Software: Jupyter Notebook 6.0.3, Python 3.7.7, Visual Studio Code 1.51

## Challenge Results
- Our target variable is 'IS_SUCCESSFUL' column.
- Our feature variables would include application type, affiliation, use case, organization, status, income amount, and special considerations.
- Variables that are neither target nor feature would be classification and ask amount.
- 2 hidden layers each with 80 and 30 neurons respectively were chosen. The activatoin functions were relu and sigmoid.
- The target 75% performance was not acheived.
- Steps taken to try and increase model performance included a third hidden layer, increasing the neurons to 100, 50, and 25 respectively, and increasing the number of epochs to 200.

## Challenge Summary
The results of this model were not nearly as promising, only managing to score a 53% accuracy. A different model to recommend would be the random forest model. This model can handle binary, categorical, and numerical features. Thus very little pre-processing needs to be done.