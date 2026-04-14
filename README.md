# ❤️ Cardiovascular Disease Risk Prediction

## 📌 Overview
This project focuses on predicting the risk of **cardiovascular disease (CVD)** using Machine Learning and Deep Learning techniques. The system analyzes lifestyle and medical factors such as BMI, smoking habits, diabetes, physical activity, and general health to identify individuals at risk.

Early prediction enables timely medical intervention and helps reduce mortality rates associated with heart diseases.

---

## 🚀 Features
- End-to-end Machine Learning pipeline
- Advanced data preprocessing and feature engineering
- Handling imbalanced datasets using SMOTE
- Multiple model training and comparison
- Deep Learning model (Artificial Neural Network)
- Model evaluation using clinically relevant metrics
- Explainable AI using SHAP

---

## 📊 Dataset
- **Source:** CDC BRFSS 2020 Dataset (`heart_2020_cleaned.csv`)
- **Records:** 319,795
- **Features:** 18

### Key Attributes:
- Demographics: Age, Sex, Race  
- Lifestyle: Smoking, Alcohol Consumption, Physical Activity  
- Medical: BMI, Diabetes, Stroke, General Health  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries & Tools:**
  - NumPy, Pandas
  - Scikit-learn
  - TensorFlow / Keras
  - XGBoost, LightGBM
  - Imbalanced-learn (SMOTE)
  - SHAP
  - Matplotlib, Seaborn

---

## 🧠 Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- XGBoost
- LightGBM
- Artificial Neural Network (ANN)

---

## 🔄 Workflow
1. Data Collection
2. Data Preprocessing
   - Binary, Ordinal, and Label Encoding
   - Feature Scaling using RobustScaler
3. Handling Class Imbalance using SMOTE
4. Model Training and Optimization
5. Model Evaluation
6. Model Explainability using SHAP

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC (Primary metric for imbalanced data)

---

## 📊 Results (Highlights)
- Ensemble models like **XGBoost** and **LightGBM** achieved strong performance
- ANN successfully captured complex nonlinear relationships
- Significant improvement in:
  - Recall (detection of actual heart disease cases)
  - F1 Score
  - PR-AUC

---

## 🧩 Key Contributions
- Designed and implemented the complete ML pipeline independently
- Developed and optimized an Artificial Neural Network using TensorFlow/Keras
- Applied SMOTE to handle severe class imbalance
- Performed comparative analysis across multiple ML and DL models
- Implemented SHAP for model interpretability and feature importance analysis
- Focused on clinically meaningful metrics rather than just accuracy

---

## 🔮 Future Scope
- Integration with real-time healthcare data (wearables, EHR systems)
- Inclusion of advanced clinical features (ECG, cholesterol, blood pressure)
- Deployment as a web or mobile application
- Use of advanced deep learning architectures (Transformers, hybrid models)
- Personalized health risk prediction systems

---

## 📚 References
- UCI Machine Learning Repository  
- WHO – Cardiovascular Diseases  
- Research papers on XGBoost, LightGBM, and SHAP  

---

## 📌 Conclusion
This project demonstrates the effectiveness of combining Machine Learning, Deep Learning, and Explainable AI for early detection of cardiovascular disease. The system serves as a reliable decision-support tool for healthcare analytics and risk prediction.
