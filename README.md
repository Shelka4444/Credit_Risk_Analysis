# Credit_Risk_Analysis
Apply machine learning to solve analyze credit card risk.


# Overview of the analysis:
The purpose of this analysis is to develop a supervised machine learning algorithms to predict credit card risk for loan management. Using different techniques to train and evaluate models with unbalanced classes, it becomes possible to determine how to better evaluate good loans versus ricky loans. Greater confidence and accuracy in building prediction models helps companies monitor fraudulent transactions, retain customers, and to build more efficient business plans for continued growth and productivity.

# Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Oversampling
<strong> Naive Random Sampling </strong>:
<p align='center'>
  <img src="https://github.com/Shelka4444/Credit_Risk_Analysis/blob/main/Resources/Images/Naive_Random_Oversampling.png" alt="Naive Random Oversampling" width=750>
</p>

The balanced accuracy score is 64%.
Due to the unbalanced nature of the data (high representation of low-risk loans to high-risk loans), the precision for high-risk loans is only 1% with a sensitivity of 66%. The F1 score for high-risk loans is 2% which does not give us confidence in using this model for detecting risky loans.

<strong> SMOTE Oversampling </strong>:
<p align='center'>
  <img src="https://github.com/Shelka4444/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE_Oversampling.png" alt="SMOTE Oversampling" width=750>
</p>

The balanced accuracy score is 65%.
Due to the unbalanced nature of the data (high representation of low-risk loans to high-risk loans), the precision for high-risk loans is only 1% with a sensitivity of 61%. The F1 score for high-risk loans is 2% which does not give us confidence in using this model for detecting risky loans.

## Undersampling
<strong> Cluster Centroids</strong>:
<p align='center'>
  <img src="https://github.com/Shelka4444/Credit_Risk_Analysis/blob/main/Resources/Images/Cluster_Centroids_Undersampling.png" alt="Cluster Centroids Undersampling" width=750>
</p>

The balanced accuracy score is 65%.
Due to the unbalanced nature of the data (high representation of low-risk loans to high-risk loans), the precision for high-risk loans is only 1% with a sensitivity of 69%. The F1 score for high-risk loans is 1% which does not give us confidence in using this model for detecting risky loans.

## Combination (Over and Under) Sampling
<strong> SMOTEENN </strong>:
<p align='center'>
  <img src="https://github.com/Shelka4444/Credit_Risk_Analysis/blob/main/Resources/Images/Combo_Sampling.png" alt="Combination Sampling" width=750>
</p>

The balanced accuracy score of 54% is lower than the previous models.
Due to the unbalanced nature of the data (high representation of low-risk loans to high-risk loans), the precision for high-risk loans is only 1% though a sensitivity score of 72% is higher than previous models. The F1 score for high-risk loans is 2% which does not give us confidence in using this model for detecting risky loans.

## Ensemble Learners
<strong> Balanced Random Forest Classifier </strong>:
<p align='center'>
  <img src="https://github.com/Shelka4444/Credit_Risk_Analysis/blob/main/Resources/Images/Balanced_Random_Forest_Classifier.png" alt="Balanced Random Forest Classifier" width=750>
</p>

The balanced accuracy score is 77%, the highest prediction score thus far.
Due to the unbalanced nature of the data (high representation of low-risk loans to high-risk loans), the precision for high-risk loans is only 3% with a sensitivity of 65%. While the F1 score for high-risk loans is 6%, this is still not substantial enough to give us confidence in using this model for detecting risky loans.

<strong> Easy Ensemble AdaBoost Classifier </strong>:
<p align='center'>
  <img src="https://github.com/Shelka4444/Credit_Risk_Analysis/blob/main/Resources/Images/Easy_Ensemble_AdaBooster_Classifier.png" alt="Easy Ensemble AdaBooster Classifier" width=750>
</p>

The balanced accuracy score is 92%.
Due to the unbalanced nature of the data (high representation of low-risk loans to high-risk loans), the precision for high-risk loans is 9% with a sensitivity of 89%. The F1 score for high-risk loans is 16% which does not give us confidence in using this model for detecting risky loans.

# Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
