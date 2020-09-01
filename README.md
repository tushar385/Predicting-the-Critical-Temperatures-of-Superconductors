# Predicting-the-Critical-Temperatures-of-Superconductors

## The steps to accomplish this task are:

1.	Open a Colab notebook.
2.	Load the necessary libraries.
3.	Read in the data from the superconduct folder.
4.	Prepare the X and y variables.
5.	Split the data into training and evaluation sets.
6.	Create a baseline linear regression model.
7.	Print out the R2 score and MSE of the model & Determined that this model is overfitting.
8.	Create a pipeline to engineer polynomial features and train a linear regression model.
9.	Print out the R2 score and MSE & Determined that this new model is overfitting.
11.Created a pipeline to engineer polynomial features and train a ridge or lasso model.
12.Print out the R2 score and MSE.Now this model is no longer overfitting. This is the model to put into production.  

   The output will be as follows:  
   Ridge Model R2 score: 0.8322365420648513
