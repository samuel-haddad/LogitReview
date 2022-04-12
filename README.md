# **Diabetes detection: Logit Model Review**
**Keywords:** GLM, GLM Logistic Regression, Logit

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)
![](https://api.visitorbadge.io/api/VisitorHit?user=samuel-haddad&repo=LogitReview&countColor=#40e0d0)

## Introduction
In this repository you will find a review about Logistic Regression with the LogisticRegression library from scikit learn.

This study was carried out using a diabetes dataset, whose dependent variable is the existence of the disease (binary logistic model). I do not intend to approach the best model for this type of challenge, but rather to explore model construction, validation plots and improvement techniques.

As always, any collaboration is welcome. So feel free to send me tips, suggestions and corrections.

Thx!


## **LogisticRegression - scikit learn** <br>
The scikit learn Logistic Regression library takes a different approach than Statsmodel and other classical libraries that use statistical testing and stepwise selection of variables. Instead of the stepwise procedure, for example, regularization procedures are used, which implies a different work of hyperparameter optimization. In this case, the basic steps are a little bit different. <br>

**Classical steps:**
1. Pre-processing
2. Model estimation
3. Analysis of the statistical significance of the variables
4. Stepwise procedure (steps 3 and 4 are repeated until all variables are statistically significant)
5. Analysis of the statistical significance of the model with Likelihood Ratio Test 6. Confusion matrix
6. Analysis of results and metrics, Sensitivity analysis, ROC curve analysis etc.
7. Model tunning (hyperparameter optimization & threshholds tunning)

<br>

**LogisticRegression (sklearn) steps:**
1. Pre-processing
2. Model Estimation
3. Analysis of results and metrics, Sensitivity analysis, ROC curve analysis etc.
4. Model tunning (hyperparam & threshholds tunning)
5. Repeat steps 2-4

**Documentação:**
<br>https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html?highlight=logisticregression#sklearn.linear_model.LogisticRegression </br>


<br> > **Bonnus track:** https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/
<br> > **Kaggle:** https://www.kaggle.com/code/haddads/diabetes-prediction/data

