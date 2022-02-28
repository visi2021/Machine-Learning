# Machine-Learning
Project - Supervised Machine Learning 
Packages to be installed and imported into Jupyter
Plotly (conda install -c plotly plotly or pip install plotly)
Pandas-Profiling (conda install -c conda-forge pandas-profiling) 
xgboost (conda install -c conda-forge xgboost followed by pip install xgboost) 

Summary:
I started this project by collecting and cleaning data followed by statistical and exploratory data analysis (EDA), using seaborn and matplotlib libraries to create visualizations, check missing data, learn which features are important, and better understand the dataset. During feature engineering and data processing, I computed missing values, converted features into numeric ones, grouped values into categories, and created new features. After data preprocessing, I trained 5 different machine learning models, picked the best one(Adaboost) based on the cross validation mean accuracy scores. Then, I briefly discussed how selected model (Adaboost) works and tuned its performance through hyperparameter optimization. I retrained the model after tunning and than evaluated the performance by reviewing the Confusion Matrix, accuracy score and classfication report that consisted of various metrics such as precision, recall, F-score.
