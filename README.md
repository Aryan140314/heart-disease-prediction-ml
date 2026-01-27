

❤️ Heart Disease Prediction using Advanced Machine Learning  

📌 Project Overview  
This project focuses on predicting the presence of heart disease using the UCI Heart Disease (Cleveland) dataset.  
It implements preprocessing, medical feature engineering, and multiple classical machine learning models to achieve high predictive performance.  

The goal is to build a robust, interpretable, and healthcare-ready ML pipeline suitable for academic, research, and real-world applications.  



📊 Dataset Information  
```Source: UCI Heart Disease Dataset (Cleveland)  
Samples: 303 patients  
Original Features: 13 clinical attributes  
Engineered Features: Medical risk indicators, ratios, and interaction terms  
Target Variable:  
0 → No heart disease  
1 → Heart disease present  
```

⚙️ Techniques Used  

🔹 Data Preprocessing  
```
Handling missing values using median imputation  
Robust scaling to handle outliers  
Stratified train–test split  
```
```🔹 Advanced Feature Engineering  
Medical risk ratios (cholesterol/age, heart rate/age)  
Cardiovascular stress indicators  
Feature interaction terms  
Composite clinical risk score  
Tree-based feature selection  
```
```🔹 Machine Learning Models  
Logistic Regression  
Decision Tree  
Random Forest  
Extra Trees  
Gradient Boosting  
AdaBoost  
Bagging  
K-Nearest Neighbors (KNN)  
Naive Bayes  
```
```🔹 Evaluation Metrics  
Accuracy  
Precision  
Recall  
F1-score  
Classification Report  
Confusion Matrix  
ROC–AUC Curve  
```


🏆 Results Summary  
```Best Performing Models:  
Gradient Boosting  
Extra Trees  
Random Forest  
```
These models achieved high F1-score and ROC–AUC, making them suitable for healthcare prediction tasks.  



📁 Project Structure  

```
healthcare_project/
├── Data/
│   ├── extracted/
│   └── processed/
├── notebooks/
│   ├── 01_ultra_preprocessing.ipynb
│   ├── 02_ultra_training.ipynb
│   └── 04_evaluation.ipynb
├── models/
├── README.md
├── requirements.txt
└── .gitignore
```

