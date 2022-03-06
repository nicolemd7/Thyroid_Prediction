## Thyroid Detection
A machine learning model used to predict whether or not a student will be placed, based on a variety of factors like
-  age                      
-  sex  
-  on_thyroxine             
-  on_antithyroid_medication  
-  sick  
-  pregnant  
-  thyroid_surgery 
-  lithium  
-  goitre    
-  tumor   
-  hypopituitary 
-  psych 
-  TSH
-  T3 
-  TT4 
-  T4U 
-  FTI 
-  TBG  
### Preprocessing ###
- All Missing Values were imputed  using KNN Imputer
- Label Encoder
- One Hot Encoder
- Oversampling to reduce imbalance in dataset
### Machine Learning Models Used ###
- K Nearest Neighbours (with hyperparameter tuning) 97.2%
- Naives Bayes 90%
- Random Forest 98.95%
- Support Vector Classifier 82.3%
- Decision Tree 98%
- Bagging 98.8%
- Gradient Boosting Classifier 97.1%
- Extreme Gradient Boosting Classifier 98.59%
- Light GBM Classifier 98.99%
- Stacking Level 1 99.91 %
- Stacking Level 2 93%
### Model Evaluation ###
- Classification Report
- ROC Curve & AUC


### Contributors ###
- Shruti Jain
- Nicole D'Souza

