# CRITERIONS_PClub

 The code implements optimization (through gradient descent) of different cost functions in a Linear and Polynomial Regression model.

###### (The code for how I generated the data is "GeneratingData.ipynb")
###### (The theta values I am using here correspond to the dataset present in CSV files.)

## Linear Regression Model:
The desired value for theta is [[15] [4]]

### For cubed error function |x -  x̂|³: 
We got, theta = [[14.99448849] [3.90734145]]


### For absolute error function |x -  x̂|:
theta turned out to be [[14.6476] [4.06246221]]



##### Both the cost functions fit the data well.
##### Comparing the theta values, we see that the absolute error function gives a slightly better theta value.

## Polynomial Regression Model:
The desired value for theta is [[1] [1] [2]]

### For "fourth-degree" error loss function |x -  x̂|⁴:
theta turned out to be [[1.01463795] [0.99882387] [1.98143011]]



### For "seventh-degree" error loss function |x -  x̂|⁷:
We got, theta = [[1.00994373] [1.02028566] [1.83644596]]




##### Both the cost functions fit the data well.
##### Looking at the graphs, the "fourth-degree" error loss function fits the data slightly better.
