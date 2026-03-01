# Industrial Fault Classification Using Supervised Learning

## 📌 Overview
This project develops a machine learning-based fault classification system for industrial hydraulic equipment using multi-sensor condition monitoring data.  
The goal is to enable predictive maintenance and reduce unexpected equipment failures.

---

## 🏭 Problem Statement
Industrial hydraulic systems generate large volumes of sensor data.  
Manual monitoring is inefficient and error-prone.  
This project builds an automated fault classification framework using supervised learning techniques.

---

## ⚙️ Dataset
- UCI Hydraulic System Condition Monitoring Dataset
- Multi-sensor industrial data (Pressure, Temperature, Vibration, Flow, Efficiency sensors)
- Time-series signals converted into statistical features

---

## 🧠 Feature Engineering
Raw time-series sensor signals were transformed into statistical features:
- Mean
- Standard Deviation
- Maximum
- Minimum

This converts high-frequency industrial signals into ML-ready structured data.

---

## 🤖 Models Implemented
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- AdaBoost
- XGBoost

---

## 📊 Evaluation Metrics
Models were evaluated using:
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🏆 Results
Ensemble learning models achieved near-perfect multi-class classification performance.  
XGBoost demonstrated superior fault detection capability across all classes.

---

## 📈 Industrial Impact
The developed system enables:
- Early fault detection
- Reduced downtime
- Predictive maintenance strategy
- Industry 4.0 monitoring applications

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---

## 📂 Project Structure
- `Industrial_Fault_Classification.ipynb` → Complete ML workflow
- `industrial_fault_classifier.pkl` → Trained model file

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Real-time deployment using Streamlit
- SMOTE for imbalance handling
- SHAP explainability integration

---

## 👨‍💻 Author
Karthik Aasish  
Machine Learning & AI Enthusiast