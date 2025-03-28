# Master-Thesis

 📊 Customer Segmentation & Churn Prediction

## 📌 Project Overview
This project applies **Machine Learning (ML) and Deep Reinforcement Learning (DQN)** to analyze customer behavior in the **telecommunications industry**. The goal is to:
- **Segment customers** based on their usage patterns
- **Predict customer churn** using supervised learning models
- **Recommend retention strategies** based on DQN-based reinforcement learning

## 📂 Dataset
We use the **Telecom Customer Churn Dataset** from Kaggle:
🔗 [Dataset Link](https://www.kaggle.com/datasets/abhinav89/telecom-customer)

### **Key Features:**
- **Demographics:** Age, income, household details
- **Usage Behavior:** Call minutes, data usage, revenue
- **Service History:** Months in service, customer care calls
- **Churn Label:** (1 = Churned, 0 = Retained)

## ⚙️ Installation
Clone the repository and install dependencies:
```bash
# Clone repo
git clone https://github.com/your-repo/customer-churn-analysis.git
cd customer-churn-analysis

# Install dependencies
pip install -r requirements.txt
```

## 🚀 Running the Code
Use Google Colab  t first load the  Dataset the  click on Run All

## 📊 Model Performance
| Model                     | Accuracy | Precision (Macro Avg) | Recall (Macro Avg) | F1-Score (Macro Avg) |
|---------------------------|----------|------------------------|---------------------|-----------------------|
| Random Forest             | 0.6119   | 0.66                   | 0.60                | 0.61                  |
| XGBoost                   | 0.6243   | 0.67                   | 0.56                | 0.62                  |
| Optimized XGBoost         | 0.6291   | 0.68                   | 0.63                | 0.63                  |
| Ensemble Voting Classifier| 0.6274   | 0.68                   | 0.56                | 0.62                  |
| Logistic Regression       | 0.5875   | 0.59                   | 0.58                | 0.59                  |


## 📌 Future Enhancements
- ✅ **Optimize DQN hyperparameters** for better segmentation
- ✅ **Introduce LSTM models** for time-series churn prediction
- ✅ **Deploy as an API for real-time churn monitoring**


