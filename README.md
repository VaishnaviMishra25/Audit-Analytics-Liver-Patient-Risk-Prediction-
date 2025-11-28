# 🩺 Audit Analytics – Liver Patient Risk Prediction  

## 📘 Project Overview  
This project predicts the likelihood of **liver disease** in patients using **machine learning techniques**.  
By analyzing healthcare data and identifying key risk factors, the model helps doctors and researchers make early, data-driven interventions for better patient outcomes.  

The project compares two algorithms  **Logistic Regression** and **Random Forest**  to identify which performs best in classifying liver patients based on their medical attributes.  

---

## 🎯 Objectives  
- Analyze patient data to predict liver disease risk.  
- Identify key clinical features influencing disease outcome.  
- Compare model performance and improve accuracy through hyperparameter tuning.  

---

## 🗂️ Dataset Information  
- **Dataset Name:** Indian Liver Patient Dataset  
- **Source:** UCI Machine Learning Repository  
- **Records:** 583 samples  
- **Features:** 11 (Age, Gender, Total Bilirubin, SGPT, SGOT, Albumin, etc.)  
- **Target Variable:**  
  - `1` → Liver Disease  
  - `2` → No Liver Disease  

---

## ⚙️ Tech Stack  
- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` → Data Analysis & Preprocessing  
  - `matplotlib`, `seaborn` → Data Visualization  
  - `scikit-learn` → Model Building & Evaluation  

---

## 🧠 Model Development  

### 🔹 Step 1: Data Preprocessing  
- Handled missing values.  
- Encoded categorical columns (e.g., Gender).  
- Normalized numerical features for uniform scaling.  

### 🔹 Step 2: Model Training  
- Built **Logistic Regression** and **Random Forest** models.  
- Split data into **train (80%)** and **test (20%)** sets.  

### 🔹 Step 3: Hyperparameter Tuning  
Used **GridSearchCV** to find the optimal parameters for Random Forest, improving accuracy and stability.  

### 🔹 Step 4: Model Evaluation  
Evaluated both models based on key metrics:  
- **Accuracy**  
- **Recall**  
- **AUC Score**  

| Model | Accuracy | Insights |
|--------|-----------|----------|
| Logistic Regression | 71.5% | Simple, interpretable baseline model |
| Random Forest | 75–80% | More robust and accurate after tuning |

---

## 📊 Visualizations  
- Feature correlation heatmap  
- Gender-wise disease distribution  
- ROC curve comparison  
- Confusion matrix visualization  

*(Add the plots from your notebook or screenshots here if available.)*  

---

## 🔍 Key Findings  
- Random Forest outperforms Logistic Regression with higher accuracy.  
- **Total Bilirubin**, **Albumin**, and **Age** were major contributors to disease prediction.  
- Proper preprocessing and tuning significantly improve model reliability.  

---

## 🔮 Future Enhancements  
- Apply **Deep Learning** (e.g., Neural Networks) for better medical predictions.  
- Build a **web-based dashboard** for real-time predictions.  
- Expand dataset with more diverse patient data.  

---

## 👩‍💻 Author  
**Vaishnavi Mishra**  
📍 *Vellore Institute of Technology (VIT)*  
🗓️ *Self-Made Project – September 2024*  

---

## 🏁 Conclusion  
This project demonstrates how machine learning can effectively support healthcare diagnostics.  
By integrating patient data analysis with predictive modeling, this system provides a foundation for future healthcare AI solutions.  

---

## ⭐ Show Your Support  
If you found this project useful, don’t forget to ⭐ **star the repository** and share it with others!
