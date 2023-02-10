# Predict-Customer-Personality-to-Boost-Marketing-Campaign-by-Using-Machine-Learning
mini project


Info & Describe

Using info function and describe, we can pull the following information from datase : 
we have 3 catagorical variables and 27 numerical variables
we have missing values for the Income Variable 

Solve Uncorrect Dtype 

we change data types
Dt_customer to datatime

Feature Extraction
(Create)
total accapted  campaign 
total purchases feature
CVR = convension rate
Age group
total spend feature
ammount of children feature
total of days joined

Drop Unnecessary Features for EDA

Unnamed: 0
 ID
Year_Birth
 Z_CostContact
 Z_Revenue
Dt_Collected

EDA

looping to categorize cat include categorical columns and num include numeric columns
Plot for categorize : numerical , categorical, and date time
We get insight based on the plot numerical are have many skewed and many outliers
Distribution categorical plot
Make a multivariate analysis for all features

Handling Missing Values

Features Income have missing values 
fill income missing value wih median

Handling Duplicated Data

Based on .duplicated() function there are 183 duplicated rows of data. But, when I try to look for it manually, i couldn't find any single of duplicated row. Then I decide to not eliminate any of this single row of data.

Feature Selection

Using RFM method to reduce dimentionality
Results Plot RFM 

Handling Outliers

Using interquartile Range



Feature Transformation
For feature M have right-skewed  distribution
Then using log transformation 


Standardization
For RFM feature 
Plotting 





