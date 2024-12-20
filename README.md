# Analysis-of-chronic-kidney-disease-using-machine-learning-techniques

## #Overview
This project leverages machine learning to analyze and detect Chronic Kidney Disease (CKD). By employing algorithms like **KNN**, **Decision Trees**, and **Naïve Bayes**, it aims to classify and predict CKD early, improving patient outcomes.

---

## #Motivation
- CKD ranks **3rd globally** and **12th in India** in mortality causes.
- Early detection significantly improves quality of life and reduces costs.
- Machine learning can help automate detection, minimizing human error and enhancing accuracy.

---

## #Objectives
- **#Preprocess** CKD datasets for efficient analysis.
- **#TrainAndEvaluate** machine learning models for CKD prediction.
- **#CompareMetrics** such as accuracy, sensitivity, precision, and F1-score.
- **#FeatureEngineering** to identify key factors in CKD detection.

---

## #Dataset
- **Source:** [Kaggle CKD Dataset](https://www.kaggle.com).
- **Attributes:** 25 features (11 numeric, 14 categorical).
- **Preprocessing:** 
  - Data cleaning.
  - Normalization.
  - Feature selection using **ANOVA**, **CHI2**, and **MRMR** algorithms.

---

## #MachineLearningModels
1. **#KNN:** Classifies based on proximity using distance metrics.
2. **#DecisionTree:** Splits data using Gini impurity and entropy.
3. **#NaiveBayes:** Applies conditional probability for classification.
4. **#SupportVectorMachine (SVM):** Adds robust classification capabilities.

---

## #ImplementationDetails
### #Workflow
1. **#DataCollection**: Gather CKD-related data.
2. **#DataPreprocessing**: Clean, normalize, and prepare datasets.
3. **#ModelTrainingTesting**: Train and test models on split datasets.
4. **#PerformanceAnalysis**: Evaluate metrics like accuracy and F1-score.

### #ToolsUsed
- **MATLAB (R2023b)**

### #EvaluationMetrics
- Accuracy
- Precision
- Sensitivity
- F1-Score
- ROC Curves

---

## #Results
- **#TrainTestSplits**: Evaluated on 67:33, 70:30, and 80:20 ratios.
- **#BestAccuracy**: Achieved with Neural Networks compared to KNN, Decision Tree, and SVM.
- **#FeatureSelection**:
  - ANOVA: Consistent accuracy with up to 22 features.
  - MRMR: Consistent accuracy with up to 16 features.
  - CHI2: Similar performance with up to 18 features.

---

## #Limitations
- Limited dataset quality and scope.
- Generalizability to diverse populations is a challenge.

---

## #FutureScope
- **#PersonalizedTreatment**: Tailor recommendations based on genetic, environmental, and lifestyle data.
- **#EnhancedModels**: Improve algorithms for CKD risk prediction and progression analysis.

---

## #References
1. K.R. Anantha Padmanaban et al., *"Applying Machine Learning Techniques for Predicting CKD Risk"*, [DOI:10.17485/ijst/2016/v9i29/93880](https://doi.org/10.17485/ijst/2016/v9i29/93880).
2. Dibaba Adeba Debal et al., *"CKD Prediction Using Machine Learning"*, [Springer Link](https://doi.org/10.1186/s40537-022-00657-5).
3. Additional references listed in the project.

---

## #Contributors
- **G.N.S. Lakshmi**
- **G. Pooja Hitha**
- **Ch. Tejaswini**
- **G. Akshitha**

### #ProjectGuides
- Mr. D. Murali Krishna (Sr. Assistant Professor)
- Mrs. T. Pavani (Associate Professor)

