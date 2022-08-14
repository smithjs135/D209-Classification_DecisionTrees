# D209-Classification_DecisionTrees
Analysis of hospital dataset using Decision Trees Classification

## Research Question
Decision trees will be used for this analysis of the medical data set to determine which features indicate whether a patient is likely to be readmitted after the initial visit.  Also, I will look to see whether readmitted patients can be grouped by defined characteristics. 

## Goal
Readmitting patients into hospitals can be a costly endeavor.  The goal of this study is to identify which patients are likely to be readmitted and provide this ability to project stakeholders to better help them curve the trend of readmission. 

## Method Justification
The target variable, ‘ReAdmis’, and various features will be fed into the decision trees function. The decision trees function uses recursive partitioning to perform attribute-value testing and then splits the data into a flow chart which it uses to make grouped-based predictions (“Decis,” p.1). 

## Packages
  * pandas
  * numpy
  * seaborn
  * matplotlib
  * sklearn.preprocessing - LabelEncoder
  * sklearn.preprocessing - StandardScaler
  * sklearn.neighbors - KNeighborsClassifier
  * sklear.model_selection - train_test_split
  * sklearn.metrics - accuracy_score
  * sklearn.metrics - classification_report
  * sklearn.metrics - confusion_matrix

## Data Preparation
Decision trees requires text variables to contain numeric data.  The target variable and some of the predictor variables contain text data.  These variables will need to be encoded to numeric values prior to using this data classification technique. 

## Selected variables
![alt_text](https://github.com/smithjs135/D209-Classification_DecisionTrees/blob/main/selected_vars.png)


## EDA
![alt_text](https://github.com/smithjs135/D209-Classification_DecisionTrees/blob/main/cp_vitdsupport.png)
![alt_text](https://github.com/smithjs135/D209-Classification_DecisionTrees/blob/main/count_plot_docvis.png)
![alt_text](https://github.com/smithjs135/D209-Classification_DecisionTrees/blob/main/corr_mat.png)


## Results
Accuracy is number of true negative plus the number of true positive predictions divided by the total number of records. Accuracy scores range from 0 (low) to 1 (high). The accuracy score of this model is 0.93 which demonstrates a high level of accuracy. 

Decision trees classification model demonstrated the ability to predict readmission rates 93% of the time based on the groupings of the feature variables. Proactive hospital staff may leverage this model to predict which patients are likely to be readmitted. 

![alt]([cp_readmis](https://github.com/smithjs135/D209-Classification_DecisionTrees/blob/main/cp_readmis.png)

## Recommendations
Decision trees classification model demonstrated the ability to predict readmission rates 93% of the time based on the groupings of the feature variables. Proactive hospital staff may leverage this model to predict which patients are likely to be readmitted. 

## Sources for Third Party Code 
1.	“Decis,”(2021, P.1). How To Plot A Confusion Matrix In Python.
How To Plot A Confusion Matrix In Python – Tarek Atwan – Notes on Artificial Intelligence. https://tatwan.github.io/How-To-Plot-A-Confusion-Matrix-In-Python
2.	“Mean Squ,”(2019, P.1). Python | Mean Squared Error. 
https://www.geeksforgeeks.org/python-mean-squared-error
3.	Avinash Navlani. (2018, P.1). Decision Tree Classification in Python Tutorial.
https://www.datacamp.com/community/tutorials/decision-tree-classification-python

## Sources(in-line)
1.	“Decis,”(2021, P.1). Decision Tree.
https://www.geeksforgeeks.org/decision-tree/
2.	Mahesh Chavan,(2021, P.1) What is Precision, Recall & F1-Score?
https://medium.com/@mahesh.chavan1997/what-is-precision-recall-f1-score-b65b1965804c
3.	Zach, (2021, P.1). MSE vs. RMSE: Which Metric Should You Use? https://www.statology.org/mse-vs-rmse
4.	Shagufta Tahsildar, (2019, P.1). Gini Index: Decision Tree, Formula, and Coefficient.
https://blog.quantinsti.com/gini-index/


