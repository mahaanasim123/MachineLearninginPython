# A Deep Dive into Customer Personality Analysis Using Machine Learning Algorithms
### Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source](#data-source)
3. [Data Software](#data-software)


## Project Objective
A key component of marketing strategy is customer personality analysis, which assists companies in comprehending the attitudes, preferences, and actions of their target market. The objective of this research is to investigate the relationship between a range of consumer characteristics, including age, income, marital status, education, and marketing campaign response. The distribution of these characteristics and how they affect consumer behavior and responses will also be examined in the investigation. Businesses can use the information to refine their marketing tactics and raise consumer satisfaction levels.       

This project was done as a part of a Machine Learning 1 (BIA 5302) course offered at Humber College, instructed by  by Dr. Salam Ismaeel. The contributors for this project are Maha Nasim, Dakshita Narain, Bhavisha Amin, Shivam Patel and Maaz Jinwala.

## Data Source

[Source](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/code)

## Data Cleaning Pre-processing
The dataset was preprocessed, which included handling missing values, eliminating duplicates, and making sure the data was consistent before it was analyzed. To improve the
reliability of the findings, outliers were addressed and categorical variables were appropriately encoded.
- The columns 'ID', 'Recency', 'Z_CostContact', and 'Z_Revenue' are dropped as these columns do not contribute to the purpose of our analysis.
- The campaign names are renamed for clear comprehension of the campaign results. “AcceptedCmp1' as 'Campaing_1', 'AcceptedCmp2' as 'Campaing_2', 'AcceptedCmp3' as
'Campaing_3', 'AcceptedCmp4' as 'Campaing_4' and 'AcceptedCmp5' as 'Campaing_5'.
-  Any missing values are filled in by using the median value of each column in the data frame.
-  After filling in the missing values, all the null values are dropped from the dataset. Now, the dataset is ready for performing exploratory analysis.

## Data Visuals 

The following graphs were used for visualing presenting our findings.
- Heat Maps
- Stacked Bar Graph
- Group Bar Graph
- Line Chart
- Pie Chart 

## Data Models
The following models were used 
1. K-Nearest Neighbors
2. Naive Bayes
3. Logistic Regression
4. Random Forest Classifier



