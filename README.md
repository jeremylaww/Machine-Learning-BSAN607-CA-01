# Machine-Learning-BSAN6070

## Computer-Assignment 1 

This program conducts an exploratory data analysis on real estate estate data with the goal to create a model to predict house prices. The dataset has 81 features that are all "potential" independent variables for predicting house prices. In this exploratory data analysis there are three steps. First we must get a understanding of our data. This was done through explorationof the data through various visualizations. From these visualizations, we are able to see which features needed to be changed in the next pre-processing stage. For instance, features with more than 60% of their rows being blank should be dropped and columns with a smaller percentage should have their blanks replaced with median values of their respective columns. 

Next, the pre-processing stage handles: missing values, handling outliers, and normaliztion. Traditionally, you would also include IDness, encoding, and stability & health checks. However, for this particiular dataset and with the specific model I was trying to make, they were not necessary.

FInally, in the post processing, I did dimnesionality reduction by taking out all other features that were concluded to not be significant enough for the model and looked out for collinearity to ensure that the model created was the best possible one. 
