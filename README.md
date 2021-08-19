# CRITERIONS_PClub

The code implements optimization (through gradient descent) of different cost functions in a Linear and Polynomial Regression model. The cost functions are further compared on how well the linear/polynomial function fits the data and how close the parameters get to the "desired parameters."

###### (The code for how I generated the data is "GeneratingData.ipynb")
###### (The theta values I am using here correspond to the dataset present in CSV files.)

## Linear Regression Model
The desired value of theta is [[15] [4]]

### For cubed error function |x -  x̂|³: 
We got, theta = [[14.99448849] [3.90734145]]

![aa](https://user-images.githubusercontent.com/86489225/130104377-19c6a94f-fbcc-4ba3-8316-3b55a3a52d91.png)

### For absolute error function |x -  x̂|:
Theta turned out to be [[14.6476] [4.06246221]]

![bb](https://user-images.githubusercontent.com/86489225/130104381-12d42ac7-4a01-42fa-b6df-4f104ee890b8.png)

##### Both the cost functions fit the data well.
##### Comparing the parameters, we see that the absolute error function gives a slightly better parameter values.

## Polynomial Regression Model
The desired value of theta is [[1] [1] [2]]

### For "fourth-degree" error loss function |x -  x̂|⁴:
Theta turned out to be [[1.01463795] [0.99882387] [1.98143011]]

![cc](https://user-images.githubusercontent.com/86489225/130104382-a9eccf1f-a74f-40f4-9d53-96b45f4efdea.png)

### For "seventh-degree" error loss function |x -  x̂|⁷:
We got, theta = [[1.00994373] [1.02028566] [1.83644596]]

![dd](https://user-images.githubusercontent.com/86489225/130104386-64d76ad3-0209-458e-a6d8-17f2bca555eb.png)

##### Both the cost functions fit the data well.
##### Looking at the graphs, the "fourth-degree" error loss function fits the data slightly better.
