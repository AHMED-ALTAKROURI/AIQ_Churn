# AIQ Churn Prediction

Churn prediction modeling and analysis, Grid search is performed on 3 classifiers the best performed classifier is used
to generate predictions on test set, saves as results.csv. SHAP values are extracted to explain models predictions.



The focus of this directory is performing experiments on different classifiers to choose for Churn Prediction problem,
There are additional work might be done for predicting outliers, Bayesian Modeling, feature imputation, imbalanced sampling.



First make sure to install requirements.txt  by typing:

```
pip install requirements.txt 
```

Make sure to install orca from npm to allow static images view from plotly:

```
npm install -g electron@1.8.4 orca

```

view all experiments results, visualizations and feature importance in:
```
modeling_and_results.ipynb

```


 





