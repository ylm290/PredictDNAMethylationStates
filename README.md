## MSc group project for [Machine Learning](https://research.vu.nl/en/courses/machine-learning-4)
**Predict CpG methylation with kNN, decision trees and SVM using different feature selection methods**

*Abstract* \
Aberrant methylation of CpGs in the human genome plays a role in diseases and aging. CpG islands are normally unmethylated and methylation can suppress gene expression.
Predicting CpG methylation could play a role in understanding the effect of methylation in disease, aging and what causes certain CpGs to be methylated or not. Using three machine learning algorithms: kNN, decision trees and SVM, we aim to find the method that is best in predicting this methylation state. Furthermore, we aim to select the most important features for this prediction. The best performing model is a decision tree, which reaches an accuracy of 0.9459 and an AUC of 0.98. The features that have the highest predictive value are the DNA patterns 'CATG', 'CGCC', 'GCGC', 'CGCG', the relative CpG position on the chromosome, if the CpG is in a promotor or island and the observed to expected ratio of the CpGs. These results show that the methylation of CpGs can be predicted with a high accuracy. This prediction could contribute to our understanding of the biological relevance and reasons for methylation.

*Data* \
(https://www.kaggle.com/competitions/predict-dna-methylation/)
