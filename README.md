# Anomaly Detection in Network Session Data

## 📌 Project Overview
This project focuses on anomaly detection in network session data using various machine learning models. The objective is to classify network sessions as normal or anomalous, ensuring robust network security by identifying suspicious activities.

## 📂 Dataset
The dataset contains network session features, including traffic patterns, protocol usage, and metadata. The target variable indicates whether a session is normal or an anomaly.

## 🏗️ Methodology
1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling and normalization
   
2. **Model Training:**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
   - XGBoost
   - LightGBM
   
3. **Hyperparameter Tuning:**
   - Using GridSearchCV to find optimal parameters
   
4. **Model Evaluation:**
   - Accuracy, ROC-AUC score
   - Classification report (Precision, Recall, F1-score)

## 🏆 Model Performance
| Model               | Train Accuracy | Test Accuracy | ROC AUC |
|---------------------|---------------|--------------|---------|
| Logistic Regression | 0.7182        | 0.7332       | 0.7987  |
| Decision Tree      | 0.8620        | 0.8679       | 0.8773  |
| Random Forest      | 0.8653        | 0.8684       | 0.8728  |
| Gradient Boosting  | 0.8763        | 0.8669       | 0.8779  |
| XGBoost           | 0.8619        | 0.8658       | 0.8799  |
| LightGBM          | 0.8620        | 0.8664       | 0.8750  |

## 📊 Key Insights
- **Tree-based models outperform Logistic Regression**, indicating that anomalies have complex, non-linear relationships.
- **XGBoost achieves the highest ROC AUC score (0.8799)**, making it the best model for ranking predictions.
- **Minimal overfitting observed** across tree-based models, as train and test accuracies are close.

## 🔧 Next Steps
- Perform feature importance analysis to identify key indicators of anomalies.
- Further optimize hyperparameters using Bayesian Optimization.
- Implement model ensembling for improved generalization.
- Deploy the best model as a web service using Flask or FastAPI.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/anomaly-detection.git
   cd anomaly-detection
   ```

## 📜 License
This project is licensed under the MIT License.

---
🙌 **Contributions are welcome!** Feel free to fork the repo and submit a pull request. 🚀

