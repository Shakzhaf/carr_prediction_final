# Car-Price-Prediction
## Problem Statement 
There an Automobile dealor which aspires which aspires to the enter the Indian Market by selling second hand cars which are kept in a showroom. They want to understand the factors affecting the pricing of cars in the market. Essentially, the company wants to know:
- Which variables are significant in predicting the price of a car?
- How well those variables describe the price of a car?
## Business Objectives:
You as a Data scientist are required to apply some data science techniques for the price of cars with the available independent variables. That should help the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels.
## The solution is divided into the following sections:
- Data understanding and exploration
- Data cleaning
- Data preparation
- Model building and evaluation

### Data understanding and exploration
Look at the columns present in your dataset in your datasets. 
![](https://github.com/Shakzhaf/carr_prediction_final/blob/main/Content/head.JPG)

#### Try to visualize data withe the help of the seaborn library.
![](https://github.com/Shakzhaf/carr_prediction_final/blob/main/Content/Visualize.JPG)

#### Data Describe
![](https://github.com/Shakzhaf/carr_prediction_final/blob/main/Content/Desvribe%20the%20data.JPG)

#### Let us visualize the correlation with the help of a heatmap
![](https://github.com/Shakzhaf/carr_prediction_final/blob/main/Content/Heatmap.JPG)<br />
We can see the car has highest correlation with kms driven kms, Pesent price. Also later during data cleaning and data processing  no. of years, transmission type and fuel type is also highly correlated.
