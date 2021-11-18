# Mid-bootcamp project - Regression





#### Table of content:
* 1 **Overview**
  - 1.1  Team 
  - 1.2 Topic
    - 1.2.1 Objective
    - 1.2.2 Scenario
    - 1.2.3 Link to the Dataset
* 2 **Timeline**
* 3 **Data exploration and preparation**
    - 3.1 Explore the data by Tableau
    - 3.2 Explore the data by MySQL
   - 3.2 Preparing the Data by Python 
* 4 **Build a Model**
    - 4.1 Round 1 
    - 4.2 Round 2 
    - 4.3 Round 3
* 5 **Summary**
#
# Predict real estate  price 
![alt text](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/Images/real-state-project.jpeg?raw=true)

## 1. **Overview**
#### 1.1  **Team**
#### DeepNoName: Glòria Ibar and Misho Gavasheli
#




#### 1.2 **Topic: Regression**

##### 1.2.1 **Objective**
###### Our job is to build a model that will predict the price of a house based on features provided in the dataset. Senior management also wants to explore the characteristics of the houses using some business intelligence tools. One of those parameters includes understanding which factors are responsible for higher property value - $650K and above.

##### 1.2.2 **Scenario**
###### We are working as an analyst for a real estate company. Our company wants to build a machine learning model to predict the selling prices of houses based on a variety of features on which the value of the house is evaluated.

##### 1.2.3 **Link to the Dataset:**
###### [Mid-bootcamp project - Regression](https://github.com/ironhack-edu/data_mid_bootcamp_project_regression)





## 2. Timeline

##### Schedule sheet

![alt text](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/Images/Screenshot%202021-11-18%20at%2011.40.41.png?raw=true)


## 3. Data exploration and preparation

##### 3.1 Explore the data by Tableau
###### We used Tableau for visualisation and exploring the data further. We saw the most expensive area, what kind of houses are most required and in which years built properties cost more

##### 3.2 Explore the data by MySQL
###### By using MySQL we tried to understand our dataset better. By answering the questions we saw better unique values of columns, in what kind of correlation are they between each other, the average price of properties, and other information and it helps to us to work with data.

##### 3.3 Preparing the Data by Python 
###### After explore the dataset we started clean and prepare it for building the models.  
###### Cleaning and preparation steps:
###### Check for NaN values and duplicates
###### Drop columns: sqft_living, sqft_lot
###### Corrected value of 33 bedrooms. After checking other metrics we decide change it for 3 bedrooms
###### Create a new column for age renovation, age of house and new date column for only month and year
###### Plots with matplot and seaborn;
###### Check dataset correlation;
###### Explore relationships between variables;


## 4. Build a Model
###### We used different models to compare the accuracies and find the model that best fits our data. 
     Our models:
              - R2
              - MSE mean_squared_error
              - Decision trees 
              - Gradient Boosting Regressor
              - SVR Support Vector Regression
              - KNN

##### 4.1 Round 1 -  Run all models 
##### 4.2 Round 2 - We dropped some columns with low correlation and removed outliers.
##### 4.3 Round 3 - we normalized and scaled the data.



## 5. Summary
