# Titanic-survival-data

### Overview
On April 15, 1912, the passenger liner Titanic  collided with an iceberg during her maiden voyage as the world's largest and fastest ship.More than 1500 passengers and crew died, making this one of the deadliest  sinkings of a single passenger ship to date.

This project comprises two parts, namely:

(i) Exploratory data analysis 
-conducted data pre-processing, which included replacing NaN values for age with mean values
-explored and visualized relationships between survival status and variables such as class and gender 

(ii) Machine learning model to predict the survival status of a passenger 
-conducted data pre-processing, which included converting categorical data to binary numbers 
-tested three models, namely decision tree, multilayer perceptron and random forest classifier
-evaluated the models using F1 and AUC-ROC scores 
-tuned the model using feature selection and improved F1 and AUC-ROC scores

### Dataset 

The principal source for data about Titanic passengers is the Encyclopedia Titanica.This data does not contain information from the crew, but it does contain actual ages of half of the passengers, as well as other information such as class of travel and gender. 

The dataset used for this project is from the Seaborn online repository which had already undergone a small amount of pre-processing. 


### Findings
(i) Women and first class passengers had a significantly higher chance of survival 

(ii) Out of the three models tested, the multilayer perceptron had the highest F1 and AUC-ROC scores
