# 🎯 Predicting Lifespan: From Age Prediction to Survival Analysis

This repository explores **predictive modeling techniques** to estimate lifespan, transitioning from **direct age prediction** to a **more advanced survival analysis approach**. The project applies **machine learning** and **deep learning models** to demographic and health-related data.

## **📂 Project Structure**
### **1️⃣ Age Prediction (Previous Approach)**
- Uses regression models to predict the **exact age of death**.
- Implemented models:
  - **XGBoost**
  - **TabNet**
  - **DF2M**
  - **MOIRAI**
- **Challenges:** Assumes all observed ages are final (ignores people still alive).

### **2️⃣ Survival Analysis (New Approach)**
- Predicts **probability of death over time**, accounting for **censored data** (people still alive).
- Models include:
  - **DeepSurv**
  - **XGBoost AFT**
  - **TabNet**
  - **EBM**
  - **LightGBM**
  - **NODE**
- **Why this matters:** More useful for real-world decisions in **healthcare, insurance, and risk assessment**.

## **⚡ Model Performance**
### **📊 Age Prediction Results**
| Model  | RMSE | MAE | R² Score |
|--------|------|-----|----------|
| **XGBoost** | 21.34 | 18.04 | -0.639 |
| **TabNet**  | 0.53 (Best Epoch) | - | - |
| **DF2M** | Results unclear | - | - |

### **📊 Survival Analysis Results**
| Model | RMSE | MAE |
|--------|------|-----|
| **XGBoost AFT** | 69.8 | 67.8 |
| **TabNet** | 15.7 | 12.4 |
| **EBM** | 15.6 | 12.3 |
| **LightGBM** | 15.6 | 12.3 |
| **NODE** | 36.5 | 27.3 |

## **📌 Why the Shift to Survival Analysis?**
### **Business Analogy:**
- Imagine an **insurance company** predicting when customers will cancel policies.
- **Old Approach:** Guess a fixed number ("they’ll cancel in 3 years").
- **New Approach:** Predict the **risk of cancellation over time**, updating as new data arrives.

### **Advantages of Survival Analysis**
✅ **Accounts for incomplete data** (e.g., living individuals).  
✅ **More useful in decision-making** (e.g., healthcare, insurance).  
✅ **Adapts to real-world uncertainty** (e.g., predicting failure rates for medical devices).  

## **🛠️ Tools Used**
- **Deep Learning:** PyTorch, Pycox, DeepSurv
- **Gradient Boosting:** XGBoost, LightGBM
- **Neural Networks:** TabNet, NODE
- **Model Deployment:** FastAPI, Docker, Google Cloud

🚀 **Future Work:** Deploying survival models as APIs for real-time predictions.
