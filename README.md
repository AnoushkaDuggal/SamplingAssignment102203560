# SamplingAssignment102203560
# Sampling Techniques and Model Accuracy Analysis

## Overview

An analysis of various sampling techniques applied to a highly imbalanced dataset, initially consisting of 763 non-fraudulent cases and only 9 fraudulent cases. To mitigate the imbalance, oversampling was employed to balance the dataset. Five different sampling methods were used to create representative samples, and multiple models were subsequently applied to each sample.

## Sampling Techniques Used

1. **Simple Random Sampling**: Random selection of samples from the population.
2. **Systematic Sampling**: Selection of samples at regular intervals after a random starting point.
3. **Cluster Sampling**: Random selection of entire clusters from the population.
4. **Stratified Sampling**: Division of the population into subgroups (strata) with samples taken from each stratum.
5. **Bootstrap Sampling**: Creation of samples by resampling with replacement from the original dataset.
   
## Models Applied

The following models were applied to each sample:

- Random Forest
- Logistic Regression
- SVM (Support Vector Machine)
- KNN (K Nearest Neighbours) 
- Gradient Boosting

## Model Accuracy Results

The accuracies of each model for the respective sampling technique are summarized in the table below:

| Sample Technique        | Random Forest | Logistic Regression | SVM    |  KNN   | Gradient Boosting |
|-------------------------|---------------|---------------------|--------|--------|-------------------|
| Simple Random Sampling  | 1.0000        | 0.8052              | 0.9610 | 0.9740 | 0.9610            |
| Systematic Sampling     | 0.9934        | 0.9079              | 0.9934 | 0.9737 | 0.9803            |
| Cluster Sampling        | 0.9934        | 0.9079              | 0.9934 | 0.9737 | 0.9803           |
| Stratified Sampling     | 0.9934        | 0.9079              | 0.9934 | 0.9737 | 0.9803            |
| Bootstrap Sampling      | 0.9934        | 0.9079              | 0.9934 | 0.9737 | 0.9803            |

