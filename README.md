# Credit Risk Analysis
Module 17: Supervised Machine Learning and Credit Risk

# Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We'll need to employ different techniques to train and evaluate models with unbalanced classes. We will use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling.

# Resources
* Data Source: LoanStats_2019Q1.csv
* Language:
  - Python
* Development tools: 
  - Visual Code 1.62.3
  - Jupyter Notebook

# Deliverables
## Deliverable #1
Use Resampling Models to Predict Credit Risk
- Algorithms used: `RandomOverSampler`, `SMOTE`, and `ClusterCentroids`

__Note__: Prior I ran the analysis with the original sample, to proof the imbalanced nature of the data, for comparison purposes.

#### __*Original Sample*__
![Deliverable #1 - OVerall](/Resources/Overall.png)

#### __*RandomOverSampler*__
![Deliverable #1 - RandomOverSampler](/Resources/RandomOverSampler.png)

#### __*SMOTE*__
![Deliverable #1 - SMOTE](/Resources/SMOTE.png)

#### __*ClusterCentroids*__
![Deliverable #1 - ClusterCentroids](/Resources/ClusterCentroids.png)


## Deliverable #2
Use the `SMOTEENN` Algorithm to Predict Credit Risk
- Algorithm used: `SMOTEENN`

#### __*SMOTEENN*__
![Deliverable #2 - SMOTEENN](/Resources/SMOTEENN.png)


## Deliverable #3
Use Ensemble Classifiers to Predict Credit Risk
- Algorithms used: `BalancedRandomForestClassifier`, and `EasyEnsembleClassifier`


#### __*BalancedRandomForestClassifier*__
![Deliverable #3 - BalancedRandomForestClassifier](/Resources/BalancedRandomForestClassifier.png)

#### __*EasyEnsembleClassifier*__
![Deliverable #3 - EasyEnsembleClassifier](/Resources/EasyEnsembleClassifier.png)

## Deliverable #4
## Analysis

### Overview of the analysis
To solve a real-world challenge, credit card risk.

### Results
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans, raw data showed a predominant number of __high risk__ loans forcing me to use different techniques to train and evaluate models with unbalanced classes or algorithms. After finishing, not sure yet about this subject, but based on the balanced accuracy scores I found, I would say, there is a certainty of .78 to .98, using the last 2 algorithms used.

### Summary
Still a lot to learn abour this subjec, I dont' feel comfortable with my analysis, and I'll have to do my best to get a more in depth knowledge.




