# Forest-Challenge
This project was developed as part of a Kaggle competition whose goal is to predict the forest cover type of a 30×30m land patch based on cartographic and geographic features. The dataset contains 15,120 labeled samples and 7 target classes corresponding to different tree species.

Our approach includes:\
	•	Exploratory Data Analysis (EDA): detection of outliers, study of feature distributions, correlations, and relationships between variables and the target.
	•	Modeling: comparison of multiple machine learning models - Logistic Regression, Random Forest, Extra Trees, SVM, KNN, XGBoost, LightGBM, CatBoost, Gradient Boosting, Neural Networks.\
	•	Best-performing strategy: a stacking ensemble using five tree-based models (Random Forest, XGBoost, LightGBM, ExtraTrees, Gradient Boosting) combined with XGBoost as a meta-model.\
	•	Performance: 90.1% accuracy on the validation set and 85.4% accuracy on the Kaggle test leaderboard\
	•	Feature engineering & preprocessing: only removal of Hillshade_9am was kept, as it consistently improved accuracy.\

