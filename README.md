# SC1015 Mini-Project
This is the SC1015 Mini-Project for Team2, Lab Group FCEE.

## About

We will be focusing on the realm of heart disease and its associated diagnostic biomarkers for our project.

We will be utilising the [Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) by David Lapp on Kaggle for our project purposes.

## Problem definition

Given diagnostic biomarkers for a patient, are we able to accurately identify if a patient has heart disease or not?

## Project Walkthrough
For a detailed walkthrough of our project, we recommend viewing our notebooks in the following order:
1. [data-extraction-and-cleaning](https://github.com/brandonleehs/SC1015-proj/blob/cvd/data-extraction-and-cleaning.ipynb)
2. [data-visualisation-and-eda](https://github.com/brandonleehs/SC1015-proj/blob/cvd/data-visualisation-and-eda.ipynb)
3. [decision-tree](https://github.com/brandonleehs/SC1015-proj/blob/cvd/decision-tree.ipynb)
4. [random-forest](https://github.com/brandonleehs/SC1015-proj/blob/cvd/random-forest.ipynb)
5. [logistic-regression](https://github.com/brandonleehs/SC1015-proj/blob/cvd/logistic-regression.ipynb)
6. [conclusion](https://github.com/brandonleehs/SC1015-proj/blob/cvd/conclusion.ipynb)

## Models Used
1. Decision tree
2. Random forest
3. Logistic regression

Based on our Exploratory Data Analysis, we come up with a few hypotheses on what may be important predictors of heart_disease

We will compare our hypothesis against the results of what the machine learning models determines are important predictors of heart_disease.

We will also explore whether attaining an extremely high accuracy with our machine learning models given a patient's diagnostic biomarkers is possible.

## What we learned
1. Quantile-Quantile plots (Q-Q) plots
2. Random Forest, Logistical Regression
3. Feature Engineering
4. Feature Importance and Selection with Permutation Feature Importance
5. Variance Inflation Factor test for multicollinearity
6. Hyperparameter tuning with GridSearchCV
7. Github Collaboration

## Contributors

@brandleehs (Lee Heng Sheng, Brandon) - Logistic Regression, data extraction, eda, conclusion
@alanlelmn (Alan Lee Leman) - Random Forest, data extraction, eda, conclusion
@27July (Wee Zi Hao (Huang Zihao))- Decision Tree, data extraction, eda, conclusion

## References
- Hair, J., Hult, G. T. M., Ringle, C. M., & Sarstedt, M. (2016). A primer on partial least squares structural equation modeling (PLS-SEM) (2nd ed.). SAGE Publications.
- Yap, L. B., Arshad, W., Jain, A., Kurbaan, A. S., & Garvie, N. W. (2005). Significance of ST depression during exercise treadmill stress and adenosine infusion myocardial perfusion imaging. The international journal of cardiovascular imaging, 21(2-3), 253–260. https://doi.org/10.1007/s10554-004-2458-y
- Brown, C. F., & Oldridge, N. B. (1985). Exercise-induced angina in the cold. Medicine and science in sports and exercise, 17(5), 607–612.
- Hill, J., & Timmis, A. (2002). Exercise tolerance testing. BMJ (Clinical research ed.), 324(7345), 1084–1087. https://doi.org/10.1136/bmj.324.7345.1084
- Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani. (2013). An introduction to statistical learning : with applications in R. New York :Springer,
- https://www.ibm.com/topics/random-forest#:~:text=Random%20forest%20is%20a%20commonly,both%20classification%20and%20regression%20problems
- https://www.geeksforgeeks.org/oob-errors-for-random-forests-in-scikit-learn/#:~:text=OOB%20(out%2Dof%2Dbag,out%2Dof%2Dbag%20samples
