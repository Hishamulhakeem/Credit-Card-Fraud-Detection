# 💳 Credit Card Fraud Detection 🔍

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using a combination of supervised and unsupervised machine learning techniques. The goal is to enhance fraud detection accuracy while maintaining computational efficiency.

## 📂 Dataset
The dataset contains transaction details such as:
- Transaction Amount
- Merchant ID
- Transaction Type
- Location
- Card Type
- Device Type
- Authentication Method
- Previous Fraudulent Transaction Indicator

Additionally, unsupervised learning techniques (DBSCAN and Isolation Forest) were applied to introduce **Cluster ID** and **Anomaly Detection** as new features.

## 🚀 Model Performance
| Metric        | Score  |
|--------------|--------|
| **Precision** | 0.99   |
| **Recall**    | 0.99   |
| **F1-score**  | 0.99   |
| **Accuracy**  | 0.9915 |
| **MAE**       | 0.0085 |

Confusion Matrix:
```
[[161   0]
 [  2  71]]
```

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Machine Learning Models:** RandomForest, XGBoost, DBSCAN Clustering, Isolation Forest

## 🔑 Key Features
- **Hybrid Approach:** Combines supervised and unsupervised learning for better fraud detection.
- **Feature Engineering:** Extracts date-time components and anomaly scores to enhance model performance.
- **Optimized for Accuracy:** Achieved a cross-validation accuracy of **99.31%**.
- **Fast Processing:** XGBoost provides faster predictions, while RandomForest delivers higher accuracy.

## 📌 Next Steps
- Automate feature engineering.
- Optimize hyperparameters for better trade-offs between accuracy and speed.
- Deploy the model using Flask, FastAPI, or a cloud-based service.

🧑‍💻 Author

Hisham ul hakeem A LinkedIn
---


