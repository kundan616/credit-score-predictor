_CREDIT SCORE PREDICTOR_
									                                   By : Kundan sharma	
                                                     
                                                     
This predictor calculates what is the chance of the client actually returning the loan given to them  , or whether the client will face some kind of financial crisis and won't be able to return the loan.
------------To run the code open creditscore.ipynb in jupyter notebook------------

1.	the first cell is mainly removing the the rows in the training data which contain any feature with NULL in it. as they may disturb the training of the network

2.	the second cell is dividing the training data into features and label file.

3.	The third cell is converting the features and label file into numpy arrays and dividing the data into training and test sets , and then scaling the data for normalisation.

4.	The forth cell is creating the neural network and and training it with the training data that we got after separating the available data into training and test sets.

5.	Fifth cell is for Saving the model for future use.

6.	Sixth cell is for evaluating the model on test data

7.	Seventh cell is for calculating the credit score on any test example , simply specify the example number between 1 and 10000.

8.	Cell 8 is for loading the pre-trained model and using it to predict credit score.

The network use for this task is a 3-layered multilayer perceptron that gives out a number between 1 and 0 as output which after further processing is used to calculate the final credit score.







