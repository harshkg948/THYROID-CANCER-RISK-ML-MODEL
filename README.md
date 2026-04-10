# 🧠 Thyroid Cancer Risk Prediction

A Machine Learning project focused on predicting thyroid cancer risk using both **unsupervised** and **supervised** learning approaches.

---

## 🚀 Project Overview

This project explores whether thyroid cancer risk can be identified:

- ❓ Without labeled data (Unsupervised Learning)
- ✅ With labeled data (Supervised Learning)

The goal was not just prediction — but understanding **how different ML approaches behave on medical data**.

---

## 📊 Approach

### 1️⃣ Unsupervised Learning (Clustering)

- Applied clustering to identify hidden risk groups
- Assumption: Data may naturally form risk-based clusters

📉 **Result:**
- Clusters (0, 1, 2) did not represent meaningful risk separation
- All risk categories were mixed

❗ **Conclusion:**
> Clustering alone was not effective for this dataset

---

### 2️⃣ Supervised Learning (Logistic Regression)

- Used labeled data to train classification model

📈 **Performance:**
- Recall: **0.51**
- F1 Score: **0.39**

---

## ⚠️ Key Insight

In healthcare problems:

> 🎯 **Recall is more important than accuracy**

Because:
- Missing a cancer case (False Negative) is critical
- Predicting risk when not present (False Positive) is comparatively safer

---

## 💡 Learnings

- Unsupervised learning may fail on complex medical datasets  
- Feature quality impacts performance more than model choice  
- Evaluation metrics must align with real-world impact  
- Even low-performing models provide valuable insights  

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 📂 Project Structure
├── data/ # Dataset
├── notebooks/ # Jupyter notebooks
├── models/ # Trained models
├── outputs/ # Graphs & results
├── README.md


---

## 🔮 Future Improvements

- 🔹 Feature Engineering  
- 🔹 Advanced Models (Random Forest, XGBoost)  
- 🔹 Hyperparameter Tuning  
- 🔹 Model Explainability (SHAP)  
- 🔹 Deployment (Flask / Streamlit)  

---

## 🤝 Contributing

Feel free to fork this repo and improve the model or suggest better approaches!

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

## 📬 Connect With Me

Let's connect and collaborate on AI & Data Science projects 🚀
