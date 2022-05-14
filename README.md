# Heart Disease Analysis-Project

# 1. Introduction
![App Screenshot](https://vitalrecord.tamhsc.edu/wp-content/uploads/2018/10/heart_research.jpg)

"Heart disease is broad term used for diseases and conditions affecting the heart and circulatory system. They are also referred as cardiovascular diseases. It is a major cause of disability all around the world. Since heart is amongst the most vital organs of the body, its diseases affect other organs and part of the body as well. There are several different types and forms of heart diseases. The most common ones cause narrowing or blockage of the coronary arteries, malfunctioning in the valves of the heart, enlargement in the size of heart and several others leading to heart failure and heart attack."

In this project, I used the dataset from kaggle.com and did Exploratory Data Analysis on the dataset and made useful conclusions about the heart disease using various factors which is causes of this problem.




# 2. Tools and Technology:


- Python with Jupter Notebook
- Numpy - It provides a fast numerical array structure and operating functions.
- Pandas - It provides tools for data storage, manipulation and analysis tasks.
- Matplotlib - It is the basic plotting library in Python. It provides tools for making plots.
- Seaborn - It is also used in visualization.
- Scikit learn - The required machine learning library in Python.


# 3. About the dataset
I downloaded the dataset from Kaggle.com . 

The dataset contains 18 variables (9 booleans, 5 strings and 4 decimals). 

# 4. Needs of This project
- Data Collection
- Data Wrangling/ Cleaning
- Data Exploration
- Visualization
- Splitting The Data for Training


# 5. Conclusions

- The result in correlation not different after normalization and also manages in covariance. The Physical health gained from 0.170721 to 0.047762 which is quite good. Meanwhile Diabetic and DiffWalking are increasing from top 5,6 to 3,4. </br>
- **From these information we can conclude features that most related to Heart Disease are: AgeCategory, Physical Health, Diabetic, DiffWalking.**
- **However, let look back to the pie charts in Binary data, we conclude in that chapter is Stroke, DiffWalking, Physical Activity, Kidney Disease, Skin Cancer affect most people in Heart Disease than people don't have Heart Disease.** 
- However, while Stroke and DiffWalking and Kidney Disease in top 6 correlation with Heart Disease, the other two have very low correlation, especially Physical Activity have negative correlation and covariance after normialization, Skin Cancer has covariance close to zero.
- We can add Kidney Disease and Skin Cancer into important features but we not sure about Physical Activity and Skin Cancer despite of most people have Heart Disease don't do Physical Activity and Skin Cancer than people who don't have Heart Disease.


