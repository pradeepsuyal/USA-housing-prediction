![Screenshot (192)](https://user-images.githubusercontent.com/86251750/142442358-158d0e20-91c7-4c04-a3d5-99d6665dd9d1.png)

Suppose Your neighbor is a real estate agent and she wants some help predicting housing prices for regions in the USA. It would be great if somehow someone creates a model for her that allows her to put in a few features of a house and returns back an estimate of what the house would sell for.

**OBJECTIVE**
--------------------------
Here I am using USA Housing Dataset for this purpose and will predict the Price of House Based on some Features.

**Dataset**
---------------------------
The datset has been added to my repository

**About the Dataset**
--------------------------
Here are what the columns represent:

'Avg. Area Income': Avg. Income of residents of the city house is located in.

'Avg. Area House Age': Avg Age of Houses in same city

'Avg. Area Number of Rooms': Avg Number of Rooms for Houses in same city

'Avg. Area Number of Bedrooms': Avg Number of Bedrooms for Houses in same city

'Area Population': Population of city house is located in

'Price': Price that the house sold at

'Address': Address for the house

## Regression Evaluation Metrics

I have used Linear Regression as the model for this Regression dataset and uses three metrics for evalution that is **MAE, RMSE and MSE.**

Here are three common evaluation metrics for regression problems:

**Mean Absolute Error** (MAE) is the mean of the absolute value of the errors:

![Screenshot (194)](https://user-images.githubusercontent.com/86251750/142446781-acbf3f3c-7979-4c19-8d79-9d81d5e77756.png)

**Mean Squared Error** (MSE) is the mean of the squared errors:

![Screenshot (195)](https://user-images.githubusercontent.com/86251750/142446933-4c3b30c9-d342-4087-bebc-239e9a047a57.png)

**Root Mean Squared Error** (RMSE) is the square root of the mean of the squared errors:

![Screenshot (193)](https://user-images.githubusercontent.com/86251750/142447011-6d0c81dc-ba91-4375-b2a0-2b5ce23687dc.png)

Comparing these metrics:

- **MAE** is the easiest to understand, because it's the average error.
- **MSE** is more popular than MAE, because MSE "punishes" larger errors, which tends to be useful in the real world.
- **RMSE** is even more popular than MSE, because RMSE is interpretable in the "y" units.

All of these are **loss functions**, because we want to minimize them.

**Model Accuracies:**
-------------------------

| Model              | MAE                |  MSE             | RMSE              |
| -------------      |:-------------:     |:-------------:   |:-------------:    |
|  Linear Regression | 82288.22251914942  |10460958907.20895 | 102278.82922290884|


***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)   ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)
