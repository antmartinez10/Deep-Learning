## Overview: 
In this project I built a **Keras Sequential Model** in order to estimate the price of a car given various values. The data can be found in the data folder in the file named audi.csv. I performed some simple **data exploration** and **data cleaning**. I also used **seaborn** to create plots in order to find out more information about the data. 


## Process/Results
First, I built a linear regression model using **sklearn.LinearRegression** to serve as a baseline for the **Keras Sequential model**. The results for the Linear Regression model were poor, as expected. Next, I built the **Keras Sequential model** that had 3 hidden layers, each with a **relu activation** function. I used the **rmsprop** optimizer and specified 100 **epochs** when fitting the model. This gave me the best results, much better than the Linear Regression model.
