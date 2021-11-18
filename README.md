# Mid-bootcamp project - Regression





#### Table of content:
* [1 **Overview**](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=1.-,Overview,-1.1%20Team)
  - [1.1  Team](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=1.1-,Team,-DeepNoName%3A%20Gl%C3%B2ria%20Ibar) 
  - [1.2 Topic](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=1.2%20Topic%3A%20Regression)
    - [1.2.1 Objective](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=1.2%20Topic%3A%20Regression-,1.2.1%20Objective,-Our%20job%20is)
    - [1.2.2 Scenario](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=650K%20and%20above.-,1.2.2%20Scenario,-We%20are%20working)
    - [1.2.3 Link to the Dataset](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=1.2.3%20Link%20to%20the%20Dataset%3A)
* [2 **Timeline**](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=bootcamp%20project%20-%20Regression-,2.%20Timeline,-Schedule%20sheet)
* [3 **Data exploration and preparation**](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=3.%20Data%20exploration%20and%20preparation)
    - [3.1 Explore the data by Tableau](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=exploration%20and%20preparation-,3.1%20Explore%20the%20data%20by%20Tableau,-We%20used%C2%A0Tableau)
    - [3.2 Explore the data by MySQL](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=properties%20cost%20more-,3.2%20Explore%20the%20data%20by%20MySQL,-By%20using%20MySQL)
   - [3.2 Preparing the Data by Python](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=3.3%20Preparing%20the%20Data%20by%20Python) 
* [4 **Build a Model**](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=relationships%20between%20variables%3B-,4.%20Build%20a%20Model,-We%20used%20different)
    - [4.1 Round 1](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=4.1%20Round%201%20-%20Run%20all%20models) 
    - [4.2 Round 2](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=4.2%20Round%202%20-%20We%20dropped%20some%20columns%20with%20low%20correlation%20and%20removed%20outliers.)
    - [4.3 Round 3](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=4.3%20Round%203%20-%20we%20normalized%20and%20scaled%20the%20data.)
* [5 **Summary**](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/README.md#:~:text=scaled%20the%20data.-,5.%20Summary,-%C2%A9%202021%20GitHub%2C%20Inc)
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
###### We used [Tableau](https://public.tableau.com/app/profile/misho.gavasheli/viz/Midbootcampproject-Regression/Dashboard?publish=yes) for visualisation and exploring the data further. We saw the most expensive area, what kind of houses are most required and in which years built properties cost more

##### 3.2 Explore the data by MySQL
###### By using [MySQL](https://github.com/mishogavasheli/Mid_bootcamp_project_Regression/blob/main/MySQL/Mid_bootcamp%20project_Regression.sql) we tried to understand our dataset better. By answering the questions we saw better unique values of columns, in what kind of correlation are they between each other, the average price of properties, and other information and it helps to us to work with data.

##### 3.3 Preparing the Data by Python 
###### After explore the dataset we started clean and prepare it for building the models.  
         Cleaning and preparation steps:
           - Check for NaN values and duplicates
           - Drop columns: sqft_living, sqft_lot
           - Corrected value of 33 bedrooms. After checking other metrics we decide change it for 3 bedrooms
           - Create a new column for age renovation, age of house and new date column for only month and year
           - Plots with matplot and seaborn;
           - Check dataset correlation;
           - Explore relationships between variables;


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
