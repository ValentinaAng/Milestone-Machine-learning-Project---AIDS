# Project Title
AIDS Clinical Trials - Machine Learning Milestone Project

# Table of Content:
1. Data Analysis
2. EDA
3. Data Preprocessing
4. Hyperparameter Tuning and Model Training
5. Model Evaluation
6. Discuss the hard points from EDA
7. Results

# Project Description
The AIDS Clinical Trials Group Study 175 Dataset contains healthcare statistics and categorical information about patients who have been diagnosed with AIDS. This dataset was initially published in 1996. The prediction task is to predict whether or not each patient died within a certain window of time or not.

# Models Used
- DecisionTreeClassifier
- RandomForestClassifier
- AdaBoostClassifier
- XGBoostClassifier

# Metrics used
- F1 score
- Precision
- Recall
- Accuracy
- ROC

# Hyperparameter Optimization Techniques
- GridSearchCV
- Bayesian Optimization
- GASearchCV

# Results
The results achieved were not optimal. The highest performance was observed with the RandomForest Classifier, which yielded an:

F1 score of 77%
recall of 77%
precision of 76%
accuracy of 89%. 

However, compared to the findings reported in this publication: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6080677/, my model's performance was lower.
There is always room for improvement:
* Handling Imbalanced Data:
**Class Weights:** Adjust class weights in the model to handle class imbalance more effectively.
**Threshold Tuning:** Optimize decision thresholds for classification to balance precision and recall.

* Consult Experts: Collaborate with domain experts to understand the problem better and incorporate domain-specific insights into the model.
* Combine Models: Try combining different models using techniques like stacking or blending to leverage their strengths.
