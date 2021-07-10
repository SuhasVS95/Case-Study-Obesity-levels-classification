# Case-Study-Obesity-levels-classification
A comparative study on Obesity/Overweight condition using binary and multiclass supervised learning classification techniques

# Problem Statement/Background
  
This dataset contains data for the estimation of obesity levels in people from the countries of Mexico, Peru and Colombia, with ages between 14 and 61 and diverse eating habits and physical condition, data was collected using a web platform with a survey where anonymous users answered each question, then the information was processed to add suitable target labels.

The paper publised for this dataset is: [1] Palechor, F. M., & de la Hoz Manotas, A. (2019). Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico. Data in Brief, 104344. https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+

# Feature Description

![image](https://user-images.githubusercontent.com/70081663/125170576-39406980-e1cd-11eb-9891-734ffed0a243.png)

# Tasks Completed:

1. Data Preprocessing and EDA
2. Analysing the performance of the model with various classification techniques.

# Summary of EDA:

1) The survey was done on 2111 people for 16 different types of variables in their lifestyle and family history.

2) Missing values have been handled using both median and KNNimputer imputation.

3) There is a strong correlation between height and weight whereas other variables have very less correlation.

4) Both Males and Females thaken in this survey are almost equal in number.

5) Target classes are BALANCED equally.

6) Most of the people use "public Transport for their commute".

7) There are more outliers in age could be due to survey concentrated more on midlle to old age people where the obesity chances are more . Other variables have negligible outliers.

8) Age is slighlty right skewed where as other variables are almost normally distributed.

9) We see with the presence of family history with obsesity, people are more likely to develop obesity.

# Experimental Results:

![image](https://user-images.githubusercontent.com/70081663/125170681-aa801c80-e1cd-11eb-94e3-fb539e32bc00.png)
