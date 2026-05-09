# hospital-readmission-predictor
ML model predicting 30-day hospital readmission using XGBoost + SHAP explainability
1. Real Medical Dataset
I used 101,766 real patient records from 130 US hospitals collected over 10 years (1999–2008). This is not fake or toy data — it's real clinical data used in actual research papers.
2. Data Cleaning
I handled missing values, removed useless columns, and converted messy text into numbers the model could understand.
3. Machine Learning Model
I trained an XGBoost classifier — the same algorithm used by winning teams in Kaggle competitions and by companies like Uber, Airbnb, and banks for predictions.
4. SHAP Explainability — My Innovation
This is the most important part. I didn't just build a model that predicts — I made it explainable. The SHAP chart shows exactly which factors push a patient toward high risk.
