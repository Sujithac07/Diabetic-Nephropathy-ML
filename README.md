# Diabetic-Nephropathy-ML
Machine Learning-Based Predictive Model for Diabetic Nephropathy

Project Description
This project focuses on developing a machine learning-based predictive model to identify and assess the severity of Diabetic Nephropathy using clinical serum biomarkers and genetic polymorphism data.

Overview
Diabetic Nephropathy (DN) is a serious complication of diabetes mellitus that can lead to chronic kidney disease and end-stage renal failure. Early diagnosis is critical for better patient outcomes. This study uses machine learning models to analyze and predict DN by leveraging key biomarkers and genetic features.

Features
Data preprocessing of clinical and genetic datasets
Exploratory Data Analysis (EDA) to explore trends and distributions
Feature engineering on inputs like gene polymorphisms, serum creatinine, albumin, etc.
Model development using:
Random Forest (achieved 84.75% accuracy)
Support Vector Machine (SVM)
Logistic Regression
Feature importance analysis to determine strong predictors
SHAP used for model interpretability

Files Included
diabetic_nephropathy_analysis.ipynb – Jupyter Notebook with full implementation
data/ – Folder for dataset files (or placeholder for instructions to access data)
model/ – (Optional) Trained model files if save
requirements.txt – Python package dependencies
README.md – This project description file

Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
SHAP for model explainability
Jupyter Notebook

Results
Random Forest model achieved the highest accuracy: 84.75%
Most significant predictors: Serum Creatinine, Albumin, Gene Polymorphisms

Authors
Sujith A C 
K. Surya Mounika
Dr. Vivekanandan T

Research Basis
This project is based on the research paper titled:
"Machine Learning-Based Predictive Model for Diabetic Nephropathy"
The study demonstrates how combining clinical and genetic data can improve early detection and personalized management of diabetic nephropathy.

Future Enhancements
Extend to multi-class classification for severity staging
Add more genetic or longitudinal patient data
Integration with hospital electronic health record (EHR) systems
