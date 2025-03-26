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
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|------------|------------|------------|------------|
| Random Forest | 83.2% | 0.82 | 0.80 | 0.81 |
| XGBoost | 85.4% | 0.84 | 0.82 | 0.83 |
| Logistic Regression | 76.5% | 0.77 | 0.75 | 0.76 |

## 📌 Future Enhancements
- ✅ **Optimize DQN hyperparameters** for better segmentation
- ✅ **Introduce LSTM models** for time-series churn prediction
- ✅ **Deploy as an API for real-time churn monitoring**


