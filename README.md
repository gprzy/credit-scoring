# Credit Scoring

<img src="https://github.com/gprzy/credit-scoring/blob/main/assets/puc.png" width="30%" height="30%"/>

[![Open in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gprzy/credit-scoring/blob/main/credit_scoring.ipynb)
[![GitHub license](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/gprzy/credit-scoring/blob/main/LICENSE)

Final project of the Data Science certifying discipline, of the Bachelor's Degree in Computer Science, at [PUCPR](). In this project, supervised learning algorithms were applied in the credit score prediction task, using data from a Brazilian financial institution.

# Problem

Credit score analysis is a task performed by numerous financial institutions, insurance companies and the like, in order to avoid potential financial losses in cases of default. In order to automate and make this process faster and more accurate, Machine Learning techniques have been adopted, making the problem become a supervised learning task (binary classification).

# Binary classification

The main goal is to classify the people in the database, whether they will be good or bad payers. In the presented problem, we have unbalanced data, making it difficult to use only metrics such as accuracy. Therefore, KS (Kolmogorov-Smirnov) was used as the main metric. Furthermore, some typical steps of data science projects were addressed, such as EDA (exploratory data analysis), pre-processing, treatment of missing values, outliers, unbalance, feature selection, among others.

Data can be obtained at (``train.csv`` and `test.csv`): https://www.ppgia.pucpr.br/~jean.barddal/datascience/

# Results

At the end of the project, a **validation KS** was obtained at **26.96** and **27.17 in test**, both using the [XGBoost](https://xgboost.readthedocs.io/en/stable/) classifier. In addition, a scientific article was also written (of which the [LaTeX](https://www.latex-project.org/) project is present in this repository), in the [IEEE](https://www.ieee.org/) standard, recording the results and details of each stage of the project.

<br>

<div align="center">
<img src="https://github.com/gprzy/credit-scoring/blob/main/assets/visualizations.jpg" width="85%" height="80%"/> <br>
Results obtained after the exploratory data analysis (EDA) stage.
</div>
