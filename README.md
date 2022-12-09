# Data_Mining_GP10

First, we downloaded a dataset from Kaggle containing information regarding the traits of potential individuals applying for credit card loans. This data contains characteristics of the people such as age, occupation, home equity payments, social security number, credit score, payment behavior, etc.

Next, we cleaned the data by breaking down the data per customer, checking for NA's in both datasets, limit amount of columns that use text to give the model more data to make predictions on, setting ID numbers as factor types, classify the credit scores into 3 categories: bad, standard, good, making all 6 payment behavior categories into binary format (True/False).

Then, we implemented as many models as possible to determine which ones worked the best if at all. The R-part and decision tree work so far. However, the KNN does not work.
