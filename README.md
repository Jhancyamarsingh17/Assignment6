# Assignment6
### Logistic Regression Model Evaluation
This repository contains an example of a logistic analysis and model evaluation on the pima indian diabetes dataset. 
### Dataset Description
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
### Business Question/ Steps done
Being able to understand the diagostic measurement and classify into diabetes or non- diabetes. 
Splitted the data into training/test sets
Inspected the data and createed a pipeline to perform any feature processing 
Created a logistic regression model pipeline that used the above pipeline
Picked a metric to select the model and justify your choice.
Used the above combined pipeline to run a Logistic Regression model with grid search cross-validation using 10 folds. Searched using 5 different regularization strengths and 2 solvers. 
### Classification Results and Predictions
As it classifcation model , we cannot define the goodness of model using accuracy. So decided to be use recall or precision. Data is about the diabetes classification , more than precision i am interested in recall so the people who are really having diabetes are not missed out. 
Recall increased from 50 % to 73 % after fitting the model with  grid search cross-validation using 10 folds, 5 different regularization strengths 0.5, 1, 1.5, 2, 10 and 2 solvers - liblinear and saga




