# German wings review challenge

The notebook shows two use cases.
The data is found in a text file holding a set of reviews about the German wings airline (airline code ‘4U’).


- ## First use case:
The goal of this use case is to show that based on the customer review data how to predict the target variable 'Recommended'.


- ## Second use case:
The goal of the second use case is to find topics in the reviews.


The notebook covers the following topics:

- #### Data loading
    - loading the customer review data from txt to dataframe

- #### EDA
    - plotting distribution of the variables
    - plotting histograms
    - showing relationship between target variables to other variables
    - text analysis
        - plotting word frequencies
        - topic modeling with LDA
    
- #### Feature engineering
    - tfidf
    - count features
    - dimensionality reduction using truncated SVD
    - word embedding
        - glove
    
- #### Evaluation
    - logloss
    - roc curve
    - precision recall curve

- #### Machine learning models
    - logistic regression
    - navie bayes
    - gradient boost machine
        - xgboost
    - deep learning
        - lstm
        - gru
        - bidirectional lstm

- #### Error analysis
