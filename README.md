# MBS-Advanced-Statistics-ML-Supply-Chain
Machine learning models applied to supply chain fraud and late delivery prediction
# Advanced Statistics - Machine Learning for Supply Chain Analytics

This repository contains the complete work for the MBS Advanced Statistics assignment.
The objective is to apply machine learning models to detect fraudulent orders and predict late deliveries using the DataCoSupplyChain dataset.

---

## 📦 Project Structure

---

##  Machine Learning Models Used

- Logistic Regression (baseline)
- Random Forest Classifier (best model)

The dataset was cleaned, encoded, imputed (median), and split into 80/20 and 70/30.
Random Forest achieved **perfect performance** on both tasks.

---

## 📊 Final Evaluation Results

| Model               | Acc (Fraud) | Recall (Fraud) | F1 (Fraud) | Acc (Late) | Recall (Late) | F1 (Late) |
|--------------------|-------------|----------------|------------|------------|----------------|------------|
| Logistic Regression | 0.976457    | 0.0            | 0.0        | 0.548333   | 1.0            | 0.708288   |
| Random Forest       | 1.000000    | 1.0            | 1.0        | 1.000000   | 1.0            | 1.0        |

---

##  Key Insights

- Logistic Regression failed to detect fraud.
- Random Forest provided perfect classification and is recommended for supply chain analytics.
- Feature importance analysis shows that delivery timing, shipping delays, and abnormal patterns are critical predictors.

---

## 📝 Author
**Houssam Tachihante**  



