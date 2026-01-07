#  Fraud Detection - Sampling Techniques on Credit Cards
a comprehensive machine learning project comparing different sampling techniques for credit card fraud detection using imbalanced dataset.

## PROJECT OVERVIEW
this project explores the impact of various sampling techniques on the performance of multiple machine learning models for credit card fraud detection. given the highly imbalanced nature of fraud detection datasets, proper sampling strategies are crucial for model performance.

## OBJECTIVES
- handle class imbalance in credit card transaction data
- compare five different sampling techniques on data
- evaluate five machine learning models on samples
- determine the best sampling-model combination

## DATASET
the project uses credit card transaction data (`creditcarddata.csv`) with features including transaction amount and a binary class label indicating fraudulent transactions.

## KEY FEATURES
- **class imbalance handling**: uses RandomOverSampler to balance the dataset before sampling
- **multiple sampling strategies**: implements 5 distinct sampling approaches
- **comprehensive model ttesting**: evaluates 5 different ML algorithms
- **reproducibility**: uses random seeds for consistent results

## RESULT STRUCTURE
for each sampling technique, the notebook provides:
- sample characteristics (size, distribution)
- accuracy scores for all five models
- easy comparison across techniques


## REFERENCES
- [scikit-learn Documentation](https://scikit-learn.org/)
- [imbalanced-learn Documentation](https://imbalanced-learn.org/)
- [Sampling Techniques in Machine Learning](https://en.wikipedia.org/wiki/Sampling_(statistics))
