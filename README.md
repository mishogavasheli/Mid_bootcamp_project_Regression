# Mid_bootcamp_project_Regression


Mid-bootcamp project - Regression.


Table of content:
1.1  Team 
1.2 Topic
1.2.1 Objective
1.2.2 Scenario
1.2.3 Link to the Dataset
2. Timeline
3.1 Explore the data by Tableau
3.1.2 Explore the data by MySQL
3.2 Preparing the Data by Python 
3.3 Build a Model
3.3.1 Round 1 
3.3.2 Round 2 
3.3.3 Round 3
4. Summary



 
1.1  Team 
DeepNoName:
Glòria Ibars
Misho Gavasheli


1.2 Topic:
Regression

1.2.1 Objective
Our job is to build a model that will predict the price of a house based on features provided in the dataset. Senior management also wants to explore the characteristics of the houses using some business intelligence tools. One of those parameters includes understanding which factors are responsible for higher property value - $650K and above.

1.2.2 Scenario
We are working as an analyst for a real estate company. Our company wants to build a machine learning model to predict the selling prices of houses based on a variety of features on which the value of the house is evaluated.

1.2.3 Link to the Dataset:
—




2. Timeline

schedule sheet

Monday	Tuesday	Wednesday	Thursday
Organise the project tasks	Stand up meeting	Stand up meeting	Stand up meeting
EDA and Cleaning 1	Review Monday’s tasks	Review Tuesday’s tasks	Prepare deliverables
Stand up meeting	Start building a model (LR)	Tableau - Regression	Readme.md
EDA and Cleaning 2	Build different models - round 1	Continue EDA, cleaning and processing data	Deliverable: File containing SQL queries
Understanding the data	KNN	Try different models	Deliverable: Python file
SQL questions	Decision trees - RANDOM FOREST		Deliverable: Tableau workbook
Explore the data in tableau			Deliverable: Presentation slides
			Deliverable: Organised repository with all the deliverables and Dataset/datasets (provided to you)


—



3.1 Explore the data by Tableau
We used Tableau for visualisation and exploring the data further. We saw the most expensive area, what kind of houses are most required and in which years built properties cost more

3.1.2 Explore the data by MySQL
By using MySQL we tried to understand our dataset better. By answering the questions we saw better unique values of columns, in what kind of correlation are they between each other, the average price of properties, and other information and it helps to us to work with data.



3.2 Preparing the Data by Python 
After explore the dataset we started clean and prepare it for building the models.  
Cleaning and preparation steps:
Check for NaN values and duplicates
Drop columns: sqft_living, sqft_lot
Corrected value of 33 bedrooms. After checking other metrics we decide change it for 3 bedrooms
Create a new column for age renovation, age of house and new date column for only month and year
Plots with matplot and seaborn;
Check dataset correlation;
Explore relationships between variables;


3.3 Build a Model
We used different models to compare the accuracies and find the model that best fits our data. 
Our models:
* R2
* MSE mean_squared_error
* SVR Support Vector Regression
* KNN
* Decision trees 
* Gradient Boosting Regressor

3.3.1 Round 1 -  Run all models 
3.3.2 Round 2 - We dropped some columns with low correlation and removed outliers.
3.3.3 Round 3 - we normalized and scaled the data.



 4. Summary
