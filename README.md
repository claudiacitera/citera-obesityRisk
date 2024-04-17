# citera-obesityRisk

## About this project
### Goal
The goal of this project is to predict the obesity risk in individuals based on different factors.

### Dataset description
The datasets (both train.csv and test.csv) contain features about the eating habits, physical condition and estimation of obesity level of people of age between 14 and 61 from Mexico, Colombia and Perù. 

Attributes related to general informations:
- Gender
- Age
- Height 
- Weight

Attributes related with eating habits: 
- Frequent consumption of high caloric food (FAVC)
- Frequency of consumption of vegetables (FCVC)
- Number of main meals (NCP) 
- Consumption of food between meals (CAEC)
- Consumption of water daily (CH20)
- Consumption of alcohol (CALC) 

Attributes related with the physical condition: 
- Calories consumption monitoring (SCC)
- Physical activity frequency (FAF)
- Time using technology devices (TUE)
- Transportation used (MTRANS)
- Family history with overweight (family_history_with_overweight)
- Smoking habit (SMOKE)

Target Attibute:
- Estimation of obesity level (NObeyesdad)

## Models
For this project, I trained and evaluated 7 different machine learning models on the given dataset, with the goal of identifying the most promising model for making predictions on the test data. The models used are:
- Decision Tree (DT)
- Random Forest (RF)
- Logistic Regression (LR)
- AdaBoost (AB)
- K-Nearest Neighbors (KNN)
- Linear Perceptron (LP)
- Support Vector Machine (SVM)

## Results
All models exhibited performance above the average, but among the seven models, five - RandomForest, SVM, DecisionTree, LogisticRegression, and KNN - achieved over 80% in all performance metrics, while the remaining two - AdaBoost and LinearPerceptron - performed at 60%.