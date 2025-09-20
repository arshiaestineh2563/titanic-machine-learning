# Titanic Survival Prediction – Machine Learning Project

This project builds and optimizes machine learning models to predict survival on the Titanic dataset.  
It demonstrates a complete *end-to-end Data Science workflow*, including data preprocessing, exploratory data analysis,  
model training, hyperparameter tuning, evaluation, and visualization of results.  

---

## 📊 Project Workflow

1. *Data Loading*
   - Titanic dataset imported from CSV.

2. *Exploratory Data Analysis (EDA)*
   - Summary statistics and missing values.
   - Correlation heatmap to understand relationships between features.

3. *Data Preprocessing*
   - Handling missing values.
   - Encoding categorical variables.
   - Feature engineering (e.g., extracting titles from passenger names).

4. *Train-Test Split*
   - Splitting data into training and testing sets.

5. *Baseline Models*
   - Logistic Regression, Decision Tree, Random Forest, SVM, KNN, XGBoost.
   - Comparison of performance across accuracy, precision, recall, and F1-score.

6. *Model Selection & Optimization*
   - Random Forest chosen for optimization.
   - *GridSearchCV* with cross-validation to find the best hyperparameters.

7. *Evaluation of Optimized Model*
   - Accuracy, Precision, Recall, F1-score.
   - Confusion Matrix visualization.
   - Metric comparison (Precision, Recall, F1, Accuracy by class).

8. *Result Analysis*
   - Strengths: strong recall for non-survivors, good precision for survivors.
   - Weaknesses: lower recall for survivors (Class 1).

9. *Conclusion & Future Work*
   - Optimized Random Forest achieved ~83% accuracy on the test set.
   - Future improvements:
     - Advanced models (XGBoost, LightGBM, CatBoost).
     - More feature engineering (family size, ticket grouping).
     - Handling class imbalance with SMOTE or class weighting.
     - Deployment as an API or interactive web app (Flask, FastAPI, Streamlit).

---

## 📈 Key Visualizations
- Correlation Heatmap of Titanic dataset.
- Confusion Matrix (optimized Random Forest).
- Classification Metrics (Precision, Recall, F1-score, Accuracy).
- Model Comparison chart across multiple algorithms.

---

## 🚀 Final Note
This project demonstrates professional-level *Data Science and Machine Learning workflow*,  
suitable for real-world applications and as a strong portfolio project for freelancing platforms like Fiverr.

---

## 👨‍💻 Author
*Arshia Estineh*  

- 📧 Email: [Arshiaestineh2005@icloud.com](mailto:Arshiaestineh2005@icloud.com)  
- 💻 GitHub: [Arshiaestineh2563](https://github.com/Arshiaestineh2563)