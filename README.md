##### CapstoneTwoProject
![alt text](https://d18zm77o7qzu1y.cloudfront.net/uploads/files/000/005/469/original/toyota_.jpg?1475163285)
# Used Vehicle Price Prediction

Buying and selling used cars online has become a major industry, ranging from individuals buying or selling their own vehicles to entire businesses that focus completely on virtual used car trading.  In this project, I used the [Used Cars Dataset](https://www.kaggle.com/austinreese/craigslist-carstrucks-data) from kaggle to develop a model that can be used to predict prices for future used cars so that potential buyers and sellers can get a fair price.  Please note that the database on kaggle is updated regularly, so the number of vehicles listed will likely be different.

### 1. Data Wrangling and Cleaning

In [this notebook](https://github.com/dawgtree/CapstoneTwoProject/blob/main/2nd_Capstone_Data_Wrangling.ipynb), I had the initial inspection of the data, selected the variables that I wanted to keep, and cleaned the data, selecting the variables that I wanted to keep.  Further details of each step I took are listed throughout the notebook.

### 2. Exploratory Data Analysis

In [this notebook](https://github.com/dawgtree/CapstoneTwoProject/blob/main/2nd_Capstone_EDA.ipynb), as I began to explore the data in more detail, I realized that more cleaning needed to be done.  I visualized the data and did hypothesis testing on the categorical variables that I predicted could determine price.  Further details of each step I took are listed throughout the notebook.

The determining variables used:\
Year Produced\
Manufacturer\
Mileage\
Cylinders\
Transmission\
Drive\
Color\
State Listed

### 3. Preprocessing and Splitting the Data

In [this notebook](https://github.com/dawgtree/CapstoneTwoProject/blob/main/2nd_Capstone_Preprocessing_Training_Data_Development.ipynb), I first split the data into training and testing set, and then assigned dummy variables to all of the categorical variables so it could be modeled.

### 4. Modeling

In [this notebook](https://github.com/dawgtree/CapstoneTwoProject/blob/main/2nd_Capstone_Modeling.ipynb), I used three different ensemble methods for regression on the data: Random Forest Regression, AdaBoost Regression, and Gradient Boosting.  I determined the RMSE, MAE, and adjusted r squared for each model to determine what was the most effective, and Random Forest consistently performed the best. Further details of each step I took are listed throughout the notebook.\
The Random Forest performance metrics:\
RMSE - 5282.47\
MAE - 2821.28\
Adjusted r squared - 0.829

[Further details of parameters used](https://github.com/dawgtree/CapstoneTwoProject/blob/main/Model%20Metrics.txt)

### 5. Reporting Data
[This pdf](https://github.com/dawgtree/CapstoneTwoProject/blob/main/Capstone%20Two%20Final%20Report.pdf) gives a detailed explanation of the entire process from the beginning and suggests the next steps that can be taken with the results.

[This presentation](https://github.com/dawgtree/CapstoneTwoProject/blob/main/2nd_Capstone_Final_Presentation.pdf) gives more of an overview of the process, along with future steps.  This is designed to be what is presented to clients.
