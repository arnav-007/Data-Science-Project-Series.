# Data-Science-Project-Series.
# DOCUMENTATION of Stock Prediction

## 1) Data Exploration and Preprocessing:

* Installed necessary libraries for analysis.

* Checked for null values and outliers in the dataset.



## 2) Dataset Manipulation:


* Created a new dataset with selected columns.

* Introduced a new column, "tomorrow," by shifting 
  values.










## 3) Target Variable Creation:


* Generated a new column, "target value," indicating 
  day-to-day change in stock price as boolean values.






## 4) Data Splitting:

* Divided the dataset into training and testing sets, 
  using the first 100 rows for training and the last 100 rows for testing.





## 5) Modeling:

* Employed various machine learning models, including 
  Random Forest, XGB Classifier, and Gradient Boosting Classifier.





## 6) Model Evaluation:

* Assessed the accuracy of each model.
* Identified XGB Classifier as the best-performing 
   model.






# DOCUMENTATION of Breast-cancer-detection




## 1) EDA (Exploratory Data Analysis):

*  Installed necessary libraries for analysis.
*  Checked for null values and outliers in the dataset.




## 2) Visualization:

* Plotted a pairplot specifically between "diagnosis" 
  and "area_worst" for initial insights.
* Extended visualization with pairplots between all 
  columns to observe changing trends.
* Created a correlation matrix to visualize 
  relationships between variables.


## 3) Data Preprocessing:

* Dropped unnecessary columns based on analysis.
* Divided the dataset into independent variables (X) and the target variable (Y) for training and testing.



## 4) Data Splitting and Training:

* Split the data into training and testing sets.
* Conducted training and testing on the divided        dataset.



## 5) Standardization:

* Standardized the data to scale down the values and ensure uniformity.


## 6) Model Implementation:

* Imported Support Vector Machine (SVM) model for classification.

## 7) Model Evaluation:

* Checked the accuracy of the SVM model.
* Calculated the R2 value to assess the model's overall performance.


