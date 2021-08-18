# ML-VideoGameSalesPrediction
Global video game sales prediction from year 2008 to 2014 approximately using linear regression and decision tree regression.
- A video game is an electronic game that involves interaction with a user interface or input device.
Since the 2010s, the commercial importance of the video game industry has been increasing. The emerging markets are driving the growth of the industry. As of 2018, video games generated sales of US$134.9 billion annually worldwide , and were the third-largest segment in the U.S. entertainment market, behind broadcast and cable TV. 
#### A regression model is built , using a linear regression model and decision tree regression model to predict the global sales , accuracy is obtained, and observations are made comparing the accuracies of both models , and the results of tuning the hyperparameters
### Steps Involved
1. At first , the important python libraries are imported to use their classes in our machine : 
- Numpy : numpy contains mathematical tools and is what we need to include any mathematical things in our code
- Pandas : it is the best library used to import and manage datasets 
2. Then we have to read our dataset 

And visualize like
![image](https://user-images.githubusercontent.com/56463608/129940162-39c776f7-0558-4715-a169-28954111125e.png)
3. Label encoding : categorical variables are variables that contain categories  [Yes or No , country names , any thing else than numbers]
this is done because as we know ML is based on mathematical equations , so strings and categorical variables would cause a problem , so we need to convert it to a representation that is suitable for computation . 
4. Then the Feature vector and dependent variable vector are extracted
5. Splitting the data into Test and train sets with ratio 80% to 20%: 
6. Scaling the data : because the variables are not on the same scale , which may cause some issues in the ML model, because most ML Models are built on Euclidean distance
 
### Building Models
1. Linear regression model observation : 
- Accuracy in the training data with Linear Regression Model:  96.50328265371722 % , 
- Accuracy in the test data with Linear Regression model 96.57734070600729 %

2. Decision tree model observation :
- Accuracy in the training data with Decision Tree Regression model:  99.82093756158373 %
- Accuracy in the test data with Decision Tree Regression model:  0.8969494361096205%

Since, accuracy is higher for Linear Regression model, so it is preferred in this case for prediction.



