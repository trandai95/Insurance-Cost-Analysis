# Insurance-Cost-Analysis
perform analytics operations on an insurance database that uses the below mentioned parameters.
Parameter|Description	|Content  | type
-------------------------------------
age	     |Age         |in years	|integer
--------------------------------------
gender	 | Male or Female	|integer| (1 or 2)
-----------------------------------------
bmi|	Body mass index|	float|
-----------------------------------------
no_of_children|	Number of children|	integer
-------------------------------------------
smoker	|Whether smoker or not	|integer | (0 or 1)
---------------------------------------------------
region|	Which US region - NW, NE, SW, SE|	integer |(1,2,3 or 4 respectively)
----------------------------------------------------------------------------
charges|	Annual Insurance charges| in USD	|float

Objectives
- Load the data as a pandas dataframe
- Clean the data, taking care of the blank entries
- Run exploratory data analysis (EDA) and identify the attributes that most affect the charges
- Develop single variable and multi variable Linear Regression models for predicting the charges
- Use Ridge regression to refine the performance of Linear regression models.

libraries:
+ skillsnetwork to download the data
+ pandas for managing the data.
+ numpy for mathematical operations.
+ sklearn for machine learning and machine-learning-pipeline related functions.
+ seaborn for visualizing the data.
+ matplotlib for additional plotting tools.
