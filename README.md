# Data_Mining_GP10

First, we downloaded a dataset from Kaggle containing information regarding the traits of potential individuals applying for credit card loans. This data contains characteristics of the people such as age, occupation, home equity payments, social security number, credit score, payment behavior, etc.

Next, we cleaned the data by breaking down the data per customer, checking for NA's in both datasets, limiting the amount of columns that use text to give the model more data to make predictions on, setting ID numbers as factor types, classify the credit scores into 2 categories in order to simplift the process by making it binary: acceptable and unacceptable, and making all 6 payment behavior categories into binary format (True/False).

Then, we implemented as many models as possible to determine which ones worked the best in terms of accuracy relative to each other. The R-part, Decision Tree, GLM, and GLMNet models are the ones that functioned well. However, the KNN and SVM models do not work well.

Finally, we decided to utilize the R-part model for our decision-making process for our credit card analysis of good predictors for loans since it upheld the greatest accuracy in terms of ROC, Sensitivity, and Specificity, relative to the other models that worked.

