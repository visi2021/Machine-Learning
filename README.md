# Machine-Learning
Project - Supervised Machine Learning 

***Very Important: Please download the .html file as it is too large to open the repository and it has my full results.  

Train.csv - Training dataset (Used for project, other datasets are for info only)

Test.csv - Test dataset

gender_submission.csv - Example of submission file to kaggle

Following are the Packages\libraries required for the project if not already installed. 

Plotly (conda install -c plotly plotly or pip install plotly)

Pandas-Profiling (conda install -c conda-forge pandas-profiling) 

or

pip install -U https://github.com/pandas-profiling/pandas-profiling/archive/master.zip

pip install -U pandas-profiling

xgboost (conda install -c conda-forge xgboost followed by pip install xgboost) 

missingno (conda install -c conda-forge missingno)

Summary:
I started this project by collecting and cleaning data followed by statistical and exploratory data analysis (EDA), using seaborn and matplotlib libraries to create visualizations, check missing data, learn which features are important, and better understand the dataset. During feature engineering and data processing, I computed missing values, converted features into numeric ones, grouped values into categories, and created new features. After data preprocessing, I trained 6 different machine learning models, picked the best one(Adaboost) based on the cross validation mean accuracy scores. Then, I briefly discussed how selected model (Adaboost) works and tuned its performance through hyperparameter optimization. I retrained the model after tunning and than evaluated the performance by reviewing the Confusion Matrix, accuracy score and classfication report that consisted of various metrics such as precision, recall, F-score followed by review of the ROC curve and AUC score.
