# Chronic-Kidney-Disease: ML-Research-Project
This is a Research project titled "Comparative Analysis of Machine Learning Models for Early Detection of Chronic Kidney Disease: A Cross-Validation Study."

Chronic Kidney Disease (CKD) is a pervasive medical condition characterized by the gradual deterioration of kidney function over time. This, CKD presents a substantial global health challenge, impacting millions of individuals Worldwide.This research conducts an in-depth comparative analysis of various machine learning algorithms for CKD prediction using a comprehensive dataset containing clinical and laboratory attributes from Kaggle. 

# Algorithms Used:
1) Support Vector Machine 
2) Random Forest
3) XGBoost

# Comparison Analysis and Result
The outcomes of the k-fold Cross-Validation scores helped to determine the performance of the models efficiently (in the given order):

1) RF: All the five cross-validation scores for Random Forest are 1.0, thus signifying the model's accuarcy to be 100% in each fold suggesting that it correctly predicted all cases in each fold.
2) XGBoost: The cross-validation ratings for XGBoost were a little erratic. They range between 0.59375 and 1.0, thus accuracy was lower(0.59375) in ceratin folds amd perfect (1.0) in others. This implies that XGBoost performed differently across different data splits.
3) SVM: Cross-validation scores for SVM vary as well, ranging from 0.75 to 0.83870968. SVM's accuracy fluctuates throughout folds, as it does with XGBoost.
  
After calculating the mean accuracy by taking the average of cross-validation results, It's concluded that overall Random forest demonstrated the highest and the most constant accuracy throughout cross validation folds followed by XGBoost and SVM.
   


 
