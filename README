# **Adult Census Income Analysis**
## **Project Overview**

This project analyzes the Adult Census Income dataset (UCI Machine Learning Repository) to explore demographic and socioeconomic factors associated with income levels. The primary objective is to understand patterns in the data and build models that predict whether an individual earns more than $50K per year.

The project is structured to highlight both data analysis (EDA, visualization, insights) and data science (feature engineering, model building).

## **Dataset Description**

Source: UCI ML Repository – Adult Dataset
Records: ~48,000 individuals (after cleaning)
Features (14 total):
Demographic: age, sex, race, marital-status
Education/Work: education, education-num, occupation, workclass, hours-per-week
Financial: capital-gain, capital-loss
Others: native-country
Target Variable: income (<=50K or >50K)

## **Analysis Questions**

1.What is the overall distribution of income (<=50K vs >50K)?
2.How does age affect the probability of earning >50K?
3.What is the relationship between education level and income?
4.Which occupations are most associated with higher income?
5.Is there evidence of a gender pay gap in this dataset?

## **Key Findings (EDA)**

According to this chart, around 75% of adults in the dataset have an income of $50k or less, while those earning more than $50k account for almost 25%.

The majority of individuals earning $50k or less are concentrated between the ages of roughly 20 and 45, with a peak around the late 20s to early 30s. In contrast, individuals earning more than $50k are more evenly distributed between their early 30s and mid-50s, peaking around the early 40s. The count of high-income individuals remains lower than that of lower-income individuals across all age groups, indicating that a greater proportion of the population falls into the ≤$50k income category.
Education: Bachelor’s degree or higher strongly increases chances of earning >50K.

Higher levels of education are strongly associated with higher income, with advanced degrees like Doctorate and Professional School showing a majority of individuals earning over $50k.

Executive and professional specialty occupations have the highest proportion of individuals earning over $50k, while roles such as private household service, other service, and handlers-cleaners have the lowest proportions.

Males have a noticeably higher proportion of individuals earning over $50k compared to females, while the majority of females fall into the ≤$50k income category.

## **Modeling**
To evaluate predictive performance, multiple machine learning models were tested. Hyperparameters were optimized using GridSearchCV (cross-validation).

**Models considered:**
    Decision Tree – baseline interpretable model.
    Random Forest – ensemble method, strong performance with feature importance ranking.
    Naive Bayes – simple probabilistic baseline.
    Support Vector Machine (SVM) – effective for classification but computationally expensive; tested with a single optimized configuration.
    Neural Network (Multilayer Perceptron) – tested with one configuration due to high training cost.

**Key Notes:**
    GridSearchCV was used for hyperparameter tuning of Decision Tree, Random Forest, and Naive Bayes.
    For SVM and MLP, a smaller set of parameters was selected due to computational constraints.
    Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.

## **Tech Stack**
Python: pandas, numpy, matplotlib, seaborn, scikit-learn
Jupyter Notebook for analysis & visualization