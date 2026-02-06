# 🧠 Diabetes Prediction with Neural Networks

This project evaluates multiple neural network architectures for predicting diabetes using structured clinical data.

---

## 📌 Overview

The objective was to classify whether a patient is likely to have diabetes using diagnostic health features.

Rather than training a single model, I built and compared three neural network architectures to evaluate how model complexity and regularization impact performance.

### Models Tested

- Baseline neural network  
- Larger neural network (no regularization)  
- Regularized neural network  

Each model was evaluated using:
- Accuracy  
- ROC-AUC  
- Confusion matrix  
- Precision / Recall  
- F1-score  

---

## 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**, which includes clinical measurements such as:

- Glucose  
- Blood Pressure  
- BMI  
- Insulin  
- Age  
- Pregnancies  
- Skin Thickness  
- Diabetes Pedigree Function  

---

## 🚀 Results

The strongest performing model was the **larger neural network (no regularization)**:

- **Test Accuracy:** 73.28%  
- **ROC-AUC:** 0.8244  

**Confusion Matrix**
[[59 16]
[15 26]]

The larger model improved ROC-AUC substantially compared to the baseline, indicating stronger overall classification ability.

---

## 🧠 Key Takeaways

- Model architecture size meaningfully impacted performance  
- Regularization reduced overfitting but lowered overall test accuracy  
- ROC-AUC provided clearer insight than accuracy alone  
- Precision and recall highlighted real-world tradeoffs  

---

## 🔮 Next Steps

- Hyperparameter tuning  
- Cross-validation  
- Logistic regression baseline comparison  
- Additional feature engineering  
