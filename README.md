# ca683Assignment_Forecast_of_bank_loans

#### Team Member:
    Chenxi Zhang
    Jianyu He
    Minhui Chen
    Yuwei Chen
    
### Procect code: https://github.com/ChyweiChen/ca683Assignment_Forecast_of_bank_loans/blob/main/CA683_Assignment_Project.ipynb
### Dataset source :https://www.kaggle.com/larsen0966/sba-loans-case-data-set       (dataset is too big to upload to Github)

This topic is to explore whether this loan is for high risk or low risk. The data used is a large and rich dataset from the Small Business Administration (SBA) in the U.S. The default rate of SBA loans has been a much debated topic in the U.S. because the SBA issues loans to customers through individual banks and if the customer defaults then the bank suffers a loss. This database used contains 27 columns with over 800,000 pieces of data. In this project data mining techniques will be used to analyse the data and build a model to predict whether the loan is a high risk loan. The main objective of the work is to predict whether a loan is high or low risk based on the SBA's dataset in order to make decisions on future applications. This in turn provides good decisions for the bank to reject or grant loan changes, thus reducing losses to the bank.


We runed 3 models , KNN,  Logistic Regression and XGBoost model.
The results of the assessment of the models are as follows.
![image](https://user-images.githubusercontent.com/33664323/115121919-15de9780-9fad-11eb-80bd-76fdd0cd901a.png)
![image](https://user-images.githubusercontent.com/33664323/115121931-242cb380-9fad-11eb-857a-e5cb3b955f0b.png)


Finally We can see here that the XGBoost model has the best results, predicting 97.2% of the data that can be repaid and 88.4% of the data that cannot be repaid, for an overall prediction accuracy of 93.7%. Good job!
