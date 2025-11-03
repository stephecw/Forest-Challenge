# 🌲 Forest Cover Type Prediction – Kaggle Challenge

This project was developed as part of a Kaggle competition whose objective is to predict the **forest cover type of a 30×30m land patch** based on cartographic and geographic features.

The dataset contains **15,120 labeled samples** and **7 target classes** corresponding to different tree species.

---

## 🔍 Project Overview

### ✅ Objectives
- Predict forest cover types using machine learning models.
- Compare classical and modern algorithms.
- Build a high-performance stacked ensemble model.

### 📊 Dataset
- **Samples:** 15,120  
- **Classes:** 7 (tree species)  
- **Features:** Topographic, soil, hydrological and hillshade data.

### 📄 Full report:  
➡️ [Click here to view the report (Rapport_Kaggle.pdf)](./Rapport_Kaggle.pdf)


### 📌 4. Performance
| Metric         | Score |
|----------------|-------|
| Validation set | **90.1% accuracy** |
| Kaggle leaderboard | **85.4% accuracy** |

### ⚙️ Workflow

1. **Data Loading**  
   Load the training and test datasets provided by Kaggle.

2. **Exploratory Data Analysis (EDA)**  
   - Feature distribution analysis  
   - Outlier detection & correlation study  
   - Relationship between variables and target classes

3. **Preprocessing**  
   - Feature engineering  
   - Removal of non-relevant variables (e.g., `Hillshade_9am`)  
   - Data normalization / encoding if necessary

4. **Modeling**  
   - Train multiple machine learning models:  
     *Logistic Regression, Random Forest, Extra Trees, SVM, KNN, XGBoost, LightGBM, CatBoost, Gradient Boosting, Neural Networks*

5. **Hyperparameter Tuning**  
   - Optimization using **Optuna**

6. **Ensemble Learning**  
   - Build a stacking model with 5 base learners:  
     *Random Forest, XGBoost, LightGBM, ExtraTrees, Gradient Boosting*  
   - Meta-model: **XGBoost**

7. **Evaluation**  
   - Validate performance on a holdout dataset  
   - Best result: **90.1% accuracy**

8. **Submission**  
   - Generate CSV submission files for Kaggle  
   - Kaggle score: **85.4% accuracy**





