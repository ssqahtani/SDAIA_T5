# Predicting body preformance
Saad Alqahtani

## Abstract
The goal of this project is to use a classification model to predict which class the individual belongs to based on their exercise performance after doing some explanatory data analysis and preprocessing.
     
## Design


## Data
The dataset contains  13393 people aged from 20 to 63 with 12 features for each, all are floats except for gender and class which are categorical. Grip Force, sit-up, broad jump, and sit and forward are exercises performed by the individuals. The rest of the features are characteristics describing the individuals.
 

## Algorithms

*Feature Engineering*

- Encoding categorical features to numerical dummy variables


*Models and its evaluation*
  
We applied Random Forest classifier and Decision Tree classifier. It turned out that Random Forest classifier outpreformed  Decision tree classifier by ~9%. Below are detalied accuracy report.

DecisionTreeClassifier:

   accuracy   0.63      
   

  


RandomForestClassifer:

 accuracy       0.71      



  
## Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and Seaborn for plotting


