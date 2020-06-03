# Heart-Disease-Risk-Prediction-and-Classification
Heart Disease Risk Prediction and Classification using various ML Algorithms and comparing their accuracies

The main objective of this project is the prediction heart disease using different classification algorithms
such as  Logistic Regression ,K-Nearest Neighbors(KNN), Support Vector Machine(SVM) ,Naïve Bayesian Algorithm,
Decision Trees and Random Forest Classifier algorithms  .The evaluation metrics used is Confusion Matrix 
and k-fold cross validation score .

Methodology

1) Import necessary libraries

2) Import Dataset .Read the datasets, the data should contain different variables like age ,sex, cp(chest pain),slope, target. 

 3) Data Visualization using histogram distribution , line and bar  graph. Use of heatmaps for determining the correlation of the various features with each other.

 4) Data Pre-processing: Dummy Variable Trap for elimination of insignificant features from the dataset , splitting of the dataset into training and test sets, feature scaling (standard scaling)

5)The Machine Learning models used for the risk prediction and  classification of heart diseases are as follows:

      i.)  Logistic Regression

      ii.)  Support Vector Machine(SVM)

      iii.)  K-Nearest Neighbors(KNN)

      iv.)   Naïve Bayesian Algorithm

       v.) Decision trees Classifier

       vi.) Random Forest  Classifier

6) Evaluation of the performance and accuracy of the various ML models employed . Evaluation metrics consisted of:
        
       1) Confusion Matrix (the visualisation of the confusion matrix consisting of the no. of actual cases and the no. of predicted cases is done in a tabulated format using the  seaborn library)
  
       2) k-fold cross validation score


7)  Plotting a bar graph for the comparison of the various test accuracies obtained by using the various ML classification algorithms.


RESULTS:
Test Accuracies obtained on various ML algorithms:
Logistic Regression=88.52%, KNN=88.52% , SVM( using rbf kernel)=85.25%
Naive Bayes =83.61% , Decision Tree Classifier(at max features:15)=85.25%
Random Forest Classifier(at no. of estimators:10)=80.33%


