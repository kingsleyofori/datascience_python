# California Housing Dataset

![California](california.jpeg)

## Story behind this Dataset

The California housing dataset is based on data from the 1990 U.S. Census. The dataset was created by Pace, R. Kelley and Ronald Barry and published in a 1997 paper titled "Sparse Spatial Autoregressions". The researchers were interested in studying the relationship between median house values and other variables in California, such as median income, average house size, and location.

To create the dataset, the researchers used information from the census along with additional data on the latitude and longitude of each house. They also applied some data cleaning and preprocessing techniques to remove missing values and outliers.

Since its publication, the California housing dataset has become a popular benchmark dataset in machine learning and data analysis. Its popularity is due in part to the fact that it is a real-world dataset with a large number of features and a non-trivial relationship between the input variables and the target variable (house prices). It has been used to build a variety of predictive models, ranging from linear regression models to deep neural networks.

## Data Description

The California housing dataset contains information about the median house value, as well as features such as the number of bedrooms, the median income of the area, and the location of the house.

The dataset has a total of 20,640 instances, each representing a block group in California. The features in the dataset are:

- MedInc: median income of the block group
- HouseAge: median age of houses in the block group
- AveRooms: average number of rooms per household in the block group
- AveBedrms: average number of bedrooms per household in the block group
- Population: total population of the block group
- AveOccup: average household size in the block group
- Latitude: latitude of the block group's location
- Longitude: longitude of the block group's location

The target variable is the median house value, which is measured in units of $100,000.

It's worth noting that the dataset is a modified version of the original dataset from the `StatLib repository`, which was collected from the 1990 US Census. The modified version was created by removing a few instances with missing values and adding the latitude and longitude coordinates.

## Project Summary


The goal of this project is to build a predictive model that can estimate housing prices in California based on various features of the houses. I will be using the California housing dataset, which contains information about the median house value, as well as features such as the number of bedrooms, the median income of the area, and the location of the house.

I will begin by exploring the dataset to get a better understanding of the data and any patterns or trends that may exist. I will then preprocess the data, including handling missing values and scaling the features. Next, I will split the dataset into training and test sets, and then build and evaluate several machine learning models using various algorithms such as linear regression, decision trees, random forests, and neural networks.

Finally, I will select the best-performing model based on evaluation metrics such as root mean squared error (RMSE), mean absolute error (MAE), and coefficient of determination (R-squared). I will also interpret the results of my analysis to gain insights into the factors that most strongly affect housing prices in California.

Overall, this project will provide a valuable opportunity for me to explore and analyze a real-world dataset, build and compare machine learning models, and gain insights into the factors that drive housing prices in California.

## Queries

Based on the dataset, here are some queries i will explore to better understand the dataset:

1. What is the distribution of median house values in the California housing dataset? Are there any outliers?
2. How are the features in the dataset correlated with each other? Are there any strong correlations that can be used for feature selection?
3. What is the distribution of median income in the areas where the houses are located? Is there a relationship between median income and median house value?
4. What is the relationship between the number of rooms in a house and its median value?
5. How are the locations of the houses distributed across California? Are there any regions with higher or lower median house values?
6. Are there any missing values in the dataset? If so, how many and what features do they pertain to?
7. What is the range of values for each feature in the dataset? Are there any features with values that are extremely high or low?

Additionally, here are some other questions to be explored:

8. Which machine learning algorithm(s) perform best on the California housing dataset?
9. Which features are most important in predicting median house values in California?
10. Can we improve the performance of our predictive model by performing feature engineering or feature selection?
11. How well does our predictive model generalize to new data?
12. Can we interpret the results of our predictive model to gain insights into the factors that most strongly affect housing prices in California?
