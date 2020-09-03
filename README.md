# Baseline-Model
Author: Mirna Salem

Date: 09/02/2020

This model learns user and item deviations from the training set and uses these values to make rating predictions. The model can be learned through statistical computation and gradient descent.  
1. Statistical Model - The global mean is calculated by finding the average of all the ratings in the training set. The user and item deviations are calculated by subtracting the global mean from the user/item's mean rating.
2. Gradient Descent - The user and item deviations are intialized with random numbers. They are learned by applying the update formulas for a specific number of epochs. 

__Yelp (ratings.csv)__:  Dataset used for building the model.

__Baseline Model - Statistical Computation.ipynb__: [Contains statistical computation model code. Click here to view it using nbviewer.](https://nbviewer.jupyter.org/github/mirna-salem/Baseline-Model/blob/master/Baseline%20Model%20-%20Statistical%20Computation.ipynb)

__Baseline Model - Stochastic Gradient Descent.ipynb__: [Contains stochastic gradient descent model code. Click here to view it using nbviewer.](https://nbviewer.jupyter.org/github/mirna-salem/Baseline-Model/blob/master/Baseline%20Model%20-%20Stochastic%20Gradient%20Descent.ipynb)
