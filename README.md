# Daniel Donohue: Machine Learning Project

For our fourth project, we participated in the Walmart recruiting challenge (to use market basket analysis to classify shopping trips) on the data science competition website [Kaggle](https://www.kaggle.com/).  My group took several different approaches to the problem, but my approach was to apply a gradient boosted tree model.  This is a strong learner, which is built from a collection of decision trees in a stagewise fashion where subsequent trees focus more on observations that were misclassified by earlier trees.  I used the Python packages [XGBoost](https://github.com/dmlc/xgboost) and [hyperopt](https://github.com/hyperopt/hyperopt).  The former is a package for gradient boosted machines, and is noted for its memory efficiency and parallelizability.  The latter is used for hyperparameter optimization.  