# deep-learning-challenge

## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special considerations for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively


## Instructions
1. Preprocess the Data
2. Compile, Train, and Evaluate the Model
3. Optimize the Model
4. Write a Report on the Neural Network Model


## Report on the Neural Network Model:
### *Overview*
The purpose of this analysis is to predict whether applicants will be successful if funded by Alphabet Soup.

### *Results*
Method 1, which is in 'Starter_Code.ipynb', had an accuracy rate of 73%, and a loss rate of 5.6%.
These rates were achieved by dropping ID columns "EIN" and "NAME". "APPLICATION_TYPE" and "CLASSIFICATION" were used for binning. There were two hidden relu layers, and 100 epochs for training the model. 

Method 2, which is in "AlphabetSoupCharity_Optimization.ipynb", had an accuracy rate of 79% and a loss rate of  4.8%. 
These rates were acheived by adding "NAME" back into the dataset. 

### *Summary*
Overall, deep learning models should have multiple layers for the computer to filter through to learn how to classify and predict information. 