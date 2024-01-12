# A Deep Dive into Customer Personality Analysis Using Machine Learning Algorithms
### Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source](#data-source)
3. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
4. [Data Visualization](data-visualization)
5. [Data Modelling](data-modelling)
6. [Conclusion](conclusion)


## Project Overview
A key component of marketing strategy is customer personality analysis, which assists companies in comprehending the attitudes, preferences, and actions of their target market. The objective of this research is to investigate the relationship between a range of consumer characteristics, including age, income, marital status, education, and marketing campaign response. The distribution of these characteristics and how they affect consumer behavior and responses will also be examined in the investigation. Businesses can use the information to refine their marketing tactics and raise consumer satisfaction levels.       

This project was done as a part of a Machine Learning 1 (BIA 5302) course offered at Humber College, instructed by  by Dr. Salam Ismaeel. The contributors for this project are Maha Nasim, Dakshita Narain, Bhavisha Amin, Shivam Patel and Maaz Jinwala.

## Data Source

[Source](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/code)

## Data Cleaning and Preprocessing
The dataset was preprocessed, which included handling missing values, eliminating duplicates, and making sure the data was consistent before it was analyzed. To improve the
reliability of the findings, outliers were addressed and categorical variables were appropriately encoded.
- The columns 'ID', 'Recency', 'Z_CostContact', and 'Z_Revenue' are dropped as these columns do not contribute to the purpose of our analysis.
- The campaign names are renamed for clear comprehension of the campaign results. “AcceptedCmp1' as 'Campaing_1', 'AcceptedCmp2' as 'Campaing_2', 'AcceptedCmp3' as
'Campaing_3', 'AcceptedCmp4' as 'Campaing_4' and 'AcceptedCmp5' as 'Campaing_5'.
-  Any missing values are filled in by using the median value of each column in the data frame.
-  After filling in the missing values, all the null values are dropped from the dataset. Now, the dataset is ready for performing exploratory analysis.

## Data Visualization

The following graphs were used for visually presenting our findings.
- Heat Maps
- Stacked Bar Graph
- Group Bar Graph
- Line Chart
- Pie Chart 

## Data Modelling
The following models were used 
1. K-Nearest Neighbors: K-nearest neighbors is a simple, instance-based learning algorithm used for classification and regression by assigning a data point the majority class or mean value of its k-nearest neighbors in the feature space.
2. Naive Bayes: Used to predict categories or classes of data by assuming that their features are independent of each other.
3. Logistic Regression: Used for binary classification, predicting the probability that an instance belongs to a particular class/ event.
4. Random Forest Classifier: An ensemble learning method that constructs a multitude of decision trees during training and outputs the mode of the classes for classification tasks.

## Conclusion 
After comparing four models, logistic regression emerges as the optimal choice for classification, exhibiting the highest accuracy (85.04%). The goal is to maximize available
resources, increase campaign effectiveness, and ultimately improve overall customer satisfaction and engagement.




