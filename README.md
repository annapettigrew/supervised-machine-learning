# supervised-machine-learning

Supervised Machine Learning Homework - Predicting Credit Risk

- In this project, I will be building a machine learning model that attempts to predict whether a loan will be approved or not.

- Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. This data will be used to create machine learning models to classify the risk level of given loans. Specifically comparing the Logistic Regression model and Random Forest Classifier.

- I start by importing the data using Pandas.

- Next, I Consider the models
    - I created and compared two models on this data: a logistic regression, and a random forests classifier. Before I created these models, I fit, and scored them, made a prediction as to which model I thought would perform better. (This is an Educated guess)

- Lastly I Fited a LogisticRegression model and RandomForestClassifier model
        - Created a LogisticRegression model, fited it to the data, and printed the model's score. And did the same for the RandomForestClassifier.

Prediction:
    - I believe that the Logistic Regression will perform better and be more accurate.
    
    - I think this because LR tends to be more accurate with numerical data while Random Forest Classifier is better with categorial data and outliers

Results:  
    - As they were close my prediction before conducting the Analysis was incorrect.  
    
    - The Random Forest Classifier ended up being slightly better and more accurate.  
    
    - I believe with the Loan status category it was an outlier vs the other data and this is what I believe made the RFC more accurate overall. 
    
    - Random Forest Classifier is more of an Accuracy focused algorithm and Random selection can capture more complex feature patterns to provide the best accuracy.
