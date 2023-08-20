# Breast Cancer Detection 

This project was done under my specialisation stream of Data Science. 

You can find the detailed documentation [here](https://docs.google.com/document/d/1dFr27aWGhaosXjnvceMp2coh_sNZEMFQLHN2zR7dbQg/edit?usp=sharing).

## Problem Statement 
To predict the breast cancer occurring in women and to analyse the category of cancer whether it is benign (B) or malignant (M) and to find out which technique will be better for prediction - SVM, Random Forest or Logistic Regression

## Data Definition
The dataset is from Wisconsin Breast Cancer Diagnostics (WBCD) obtained from UCI Repository. The  data consists of 32 characteristics of tumour for 569 patients.


Ten real-valued features are computed for each cell nucleus:
- radius (mean of distances from center to points on the perimeter) 
- texture (standard deviation of gray-scale values) 
- perimeter 
- area 
- smoothness (local variation in radius lengths) 
- compactness (perimeter^2 / area - 1.0) 
- concavity (severity of concave portions of the contour) 
- concave points (number of concave portions of the contour) 
- symmetry 
- fractal dimension ("coastline approximation" - 1)


The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
Data was acquired from Kaggle [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

## Workflow or Approach

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
5. Model Building
6. Conclusion

## Feature Engineering 

The performance of our code in predicting whether it is benign (B) or malignant (M) increases when we choose the most significant attributes and reduce the size of our data collection (M). Hence it is important to perform feature engineering and test the addition or subtraction of variables from our data set to improve accuracy.


After exploring the data and visualizing it in different ways, one visualization that stood different was corelation. Multicollinearity was observed between various columns. This was further confirmed by pairplotting those columns.

To better understand which variable gives us better accuracy we have tested it on different combination of column variables, like:
- Without dropping the worst columns
- After dropping few worst columns that show high multicollinearity
- After dropping all the worst columns


The different models we have used to for prediction are:
- Logistic Regression
- Random Forest
- SVM

## Model Building

![](https://github.com/saij19/Breast-Cancer-Detection/blob/ded91df7785d77ef1c4d8ce97fd00cccd27ae415/model_ch.png)

## Conclusion

Concluded this project by predicting whether it is benign (B) or malignant (M) by iterating multiple models on different combinations of columns in the data set. This early detection of cancer can help save the patient by providing healthcare services on time.


I applied various data cleaning, exploratory data analysis techniques to our data for better understanding and visualization. 
