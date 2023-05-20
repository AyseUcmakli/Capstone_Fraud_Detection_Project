# Capstone_Fraud_Detection_Project

<img src= "https://www.businessprocessincubator.com/wp-content/uploads/2018/10/www.fico_.comFraud-Management-Team-FIC-83f57a6ec467fcf8c7f911e7cbe2a56f802515b2.jpg" width = 600, height =600>

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where it has 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Feature Information:

Time: This feature is contains the seconds elapsed between each transaction and the first transaction in the dataset.

Amount: This feature is the transaction Amount, can be used for example-dependant cost-senstive learning.

Class: This feature is the target variable and it takes value 1 in case of fraud and 0 otherwise.

The aim of this project is to predict whether a credit card transaction is fraudulent. Of course, this is not easy to do. First of all, we need to analyze and recognize our data well in order to draw your roadmap and choose the correct arguments we will use. Accordingly, we can examine the frequency distributions of variables. we can observe variable correlations and want to explore multicollinearity. we can display the distribution of the target variable's classes over other variables. Also, it is useful to take missing values and outliers.

After these procedures, we can move on to the model building stage by doing the basic data pre-processing you are familiar with.

Start with Logistic Regression and evaluate model performance. We will apply the Unbalanced Data Techniques used to increase the performance. Next, observe their effects.

Then, we will use four different algorithms in the model building phase.

In the final step, we will deploy your model using Streamlit API.

Optional: We can Dockerize your project and deploy on cloud.

#### 1. Exploratory Data Analysis & Data Cleaning

- Import Modules, Load Data & Data Review
- Apply data integrity checks
- Exploratory Data Analysis
- Data Cleaning
    
#### 2. Data Preprocessing

- Train - Test Split
- Train - Test Split Validation Checks
- Scaling

#### 3. Model Building

- Logistic Regression 
- Random Forest Classifier
- XGBoost Classifier
- Neural Network
- 

#### 4. Model Deployement

- Save and Export the Best Model
- Save and Export Variables
